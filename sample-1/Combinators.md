Combinators

## Adjacent Sibling

h2 + p {
    color: red;
}

```
    <div>
        <h2>Not Applied</h2>
        <p>CSS Applied</p>
        <h2>Not Applied</h2>
        <h3>Not Applied</h3>
        <p>Not Applied</p>
        <h2>Not Applied</h2>
        <p>CSS Applied</p>
    </div>
```
--

## General Sibling

h2 ~ p {
    color: red;
}

```
    <div>
        <h2>Not Applied</h2>
        <p>CSS Applied</p>
        <h2>Not Applied</h2>
        <h3>Not Applied</h3>
        <p>CSS Applied</p>
    </div>
```
--
## Child

h2 > p {
    color: red;
}

```
    <div>
        <div>Not Applied</div>
        <p>CSS Applied</p>
        <div>Not Applied</div>
        <article>
            <p>Not Applied</p>
        <article>    
        <p>CSS Applied</p>
    </div>
```
--
## Decendant

h2 p {
    color: red;
}

```
    <div>
        <div>Not Applied</div>
        <p>CSS Applied</p>
        <div>Not Applied</div>
        <article>
            <p>CSS Applied</p>
        <article>    
        <p>CSS Applied</p>
    </div>
```
--