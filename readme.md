#### usage

####base
```css
element {
    ...
    width: 743px;
    height: 178px;
    background: url("../images/about-header-bg.png") center center no-repeat;
    ...
}
```

####response
```css
element {
    ...
    @media (max-width: 1200px) {
        width: 650px;
        height: scaler(743, 178, 650);
        background-size: 100%;
    }
    ...
}
```

**Author**
Martin Fugess
