# Transiciones

### transition

* property
* duration
* delay
* timing-function

#### Shorthand: transition: property duration delay timing-function

# @keyframes

### Declaración

```
@keyframes ejemplo {
    0% { color: red, font-size: 4px }
    25% { background-color: yellow; }
    50% {...}
    100% {...}
}
```
### Llamada

```
p#animado {
    animation-name.anim1
}
```

### Propiedades
* animation-name
* animation-duration
* animation-delay
* animation-timing-function
* animation-direction
* animation-iteration-count


#### Shorthand
```
animation: name duration timing-function delay iteration-count direction fill-mode play-state
```