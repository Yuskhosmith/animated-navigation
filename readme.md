# Hello 🌚

This project animates the hamburger manu to slide in and out.

You can checkout [my last project](https://yuskhosmith.github.io/animated-template) which animates a template website built with tailwind CSS, using the [animate on scroll library](https://michalsnik.github.io/aos/) built by michalsnik.

## .New
I learnt the how to use CSS animation
```css
/* Slide in animation with delay for each nav item */
.slide-in-1{
  animation: slide-in 0.4s linear 0.2s both;
}
.slide-in-2{
  animation: slide-in 0.4s linear 0.4s both;
}
.slide-in-3{
  animation: slide-in 0.4s linear 0.6s both;
}
.slide-in-4{
  animation: slide-in 0.4s linear 0.8s both;
}
.slide-in-5{
  animation: slide-in 0.4s linear 1s both;
}

@keyframes slide-in {
  from {
    transform: translateX(-100%);
  }

  to{
    transform: translateX(0);
  }
}

```

[Live Site](https://yuskhosmith.github.io/animated-navigation/)