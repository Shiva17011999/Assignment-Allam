# Assignment-Allam
# Allam Shiva Kumar
#### Kakatiya Museum

A classic and a **historcal** site located in one of the major cities of the state **Telangana**

---
### Directions to the museum from the Airport

The Warangal Mamnoor airport is the nearest airport to the museum
It is located in the Warangal district of Telangana State, India.
1. Board the warangal bus stop or Railway station<br>
2. You will have the direct cabs and autos<br>

Places near the museum
- Bhadrakali Temple
- Ram Laxman Theatre
- Kila Warangal Fort

[Link to my About Me](https://github.com/Shiva17011999/Assignment2-Allam/blob/main/AboutMe.md)
---
### Tables
This table shows my recommendation to 4 different places one should definitely visit.
| City | Location | Time |
| --- | --- | ---: |
| Goa | Beach <br> Church| 2 hours <br> half day |
| Maryville | Mozingo | 3 hours |
| Bangalore | Wonderla <br> Mysore Palace | 6 hours <br> 3 hours |
| Delhi | Red Fort <br> Qutub Minar | 2 hours <br> 2 hours |

---
### Pithy quotes
>Your attitude, not your aptitude, will determine your altitude. -*Zig Ziglar* <br>
>Don't give up -*Sri Tarun*

---
### Code Fencing 
>Material Shadows Mixin
[stack overflow link](https://stackoverflow.com/questions/30533055/calculating-shadow-values-for-all-material-design-elevations/52740764#52740764)
```
/// Gives a card depth effect.
/// @param {Number} $depth - depth level (between 1 and 5)
/// @link http://www.google.com/design/spec/layout/layout-principles.html#layout-principles-dimensionality Google Design
/// @requires {function} top-shadow
/// @requires {function} bottom-shadow
@mixin card($depth) {
  @if $depth < 1 {
    box-shadow: none;
  } @else if $depth > 5 {
    @warn "Invalid $depth `#{$depth}` for mixin `card`.";
  } @else {
    box-shadow: bottom-shadow($depth), top-shadow($depth);  
  }
}
```
[css-tricks-link](https://css-tricks.com/snippets/sass/material-shadows-mixin/)



