__________________________________________________________________________________________________________________
# Aleksey Lazarev
__________________________________________________________________________________________________________________
## Contacts
__________________________________________________________________________________________________________________
#### * Location: Serbia
#### * Phone: +381637688442
#### * E-mail: fojcsog@gmail.com
#### * GitHub: lazleha

## About Me
__________________________________________________________________________________________________________________
#### I studied to be a KIPiA fitter and I work, but I can't get rid of the desire: to program. And I strive for the goal...

## Skills
__________________________________________________________________________________________________________________
#### * HTML
#### * CSS
#### * JavaScript
#### * Git

## Code Example
__________________________________________________________________________________________________________________

`let slideIndex = 1;`
`let timer;` 

```
window.addEventListener("load", () => {
  showSlides(slideIndex);
});
```
```
function plusSlides(n) {
  showSlides((slideIndex += n));
}
```
```
function currentSlide(n) {
  showSlides((slideIndex = n));
}
```
```
function showSlides(n) {
  const slides = document.getElementsByClassName("mySlides");
  const dots = document.getElementsByClassName("dot");

  if (n > slides.length) {
    slideIndex = 1;
  }
  if (n < 1) {
    slideIndex = slides.length;
  }

  for (let i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  

  for (let i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }

  slides[slideIndex - 1].style.display = "block";

  dots[slideIndex - 1].className += " active";

  clearTimeout(timer);
  timer = setTimeout(() => plusSlides(1), 5000);
}
```

## Education
__________________________________________________________________________________________________________________

### Modern school of knowledge
#### * Basics of web programming.



