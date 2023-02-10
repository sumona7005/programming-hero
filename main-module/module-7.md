# Note

- shortcut: `.box#box-$*4`
- `visibility: hidden` vs `display: none` , show: `display: block`
- overflow:
  - `overflow: hidden` , `overflow: scroll`
  - `overflow: scroll` + `overflow-x: hidden` / `overflow-y: scroll`
  - `white-space: nowrap` , `overflow: hidden` , `text-overflow: ellipsis` , `title`
- image optimization: photoshop, photopea, tinypng
- add icons using fontawesome
- transform:
  - `transform: scale(1.2)`
  - `transform: rotate(30deg)`
  - `transform: translate(50px)`
- transition:
  - `transition: property duration timing delay`
    - `transition: width 2s linear 1s, height 2s ease 4s`
    - `transition: width 1s, height 1s, transform 2s`
  - `:hover` (changes I need)
    - `height` , `width` , `transform`
- cricket animation:
  - bat
    - `transition: transform 0.5s ease-in`
  - ball
    - `position: relative`
    - `left: 400px`
    - `transition: transform 1s ease-out 0.5s`
  - bat after hover
    - `transform: rotate(-60deg)`
    - `transform-origin: top right`
  - ball after hover
    - `transform: translate(400px, -50px)`
- bounce ball - animation:
  - `position: relative`
  - `animation: name duration timing-function delay iteration-count direction fill-mode`
  - `animation: sliding 2s ease-in-out 0.5s infinite alternate`
  - `animation-play-state: running`
  - `@keyframes name{}`
    - `from{} to{}` / `0%{} 50%{} 100%{}`
      - `background-color`
      - `top` , `left`
      - `transition: scale()`
- shortcut: `.container` , `.box*4>p>lorem30`
- `float` , `cursor` , `min-height` , `max-height`

# Coding File

- [visibility vs display](/coding-file/7-visibility.html)
- [overflow](/coding-file/7-overflow.html)
- [fontawesome](/coding-file/7-fontawesome.html)
- [transform](/coding-file/7-transform.html)
- [transition](/coding-file/7-transition.html)
- [cricket animation](/coding-file/7-cricket-animation.html)
- [bounce ball](/coding-file/7-bounce-ball.html)
- [float](/coding-file/7-float.html)

# Screenshot

![](/screenshot/36.png)
![](/screenshot/37.png)