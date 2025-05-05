# Essential Stuff

## Html import links

Google font

``` html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link
  href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&family=Roboto:wght@400;700&family=Saira+Stencil+One&display=swap"
  rel="stylesheet">
```

Ionicon

``` html
<script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
```

---

## Colors

``` css
--raw-seinna: hsl(24, 74%, 58%);
--sizzling-sunrise: hsl(51, 95%, 54%);
--scarlet: hsl(13, 96%, 47%);
--black: hsl(0, 0%, 0%);
--white: hsl(0, 0%, 100%);
```

## Typography

``` css
--ff-saira-stencil-one: "Saira Stencil One", sans-serif; 
--ff-poppins: 'Poppins', sans-serif;
--ff-roboto: 'Roboto', sans-serif;

--fs-1: 2rem;
--fs-2: calc(1.813rem + 1vw);
--fs-3: calc(1.313rem + 1vw);
--fs-4: 1.4rem;
--fs-5: 1rem;
--fs-6: 0.813rem;
--fs-7: 0.75rem;

--fw-400: 400;
--fw-700: 700;
```

## Transition

``` css
--transition-1: 0.25s ease-in-out;
```

## Spacing

``` css
--section-padding: 80px;
```

## Border radius

``` css
--radius-4: 4px;
--radius-12: 12px;
```

---

## Theme Variables

### Dark Mode

``` css
--bg-primary: hsl(0, 0%, 12%);
--bg-secondary: hsl(0, 0%, 19%);
--color-primary: hsl(0, 0%, 100%);
--color-secondary: hsl(0, 0%, 62%);
--card-shadow: hsla(0, 0%, 0%, 0.4);
--input-bg: hsl(0, 0%, 16%);

--shadow-1: 10px 10px 40px var(--card-shadow);
```

### Light Mode

``` css
--bg-primary: hsl(0, 0%, 90%);
--bg-secondary: hsl(0, 0%, 100%);
--color-primary: hsl(0, 0%, 12%);
--color-secondary: hsl(0, 0%, 37%);
--card-shadow: hsla(0, 0%, 0%, 0.1);
--input-bg: hsl(0, 0%, 93%);

--shadow-1: 10px 10px 40px var(--card-shadow);
```

.hero {
  min-height: 100vh;
  display: flex;
  align-items: center;  /* center vertically */
  justify-content: center;  /* center horizontally */
  background-color: var(--bg-primary);
  padding: 0 var(--section-padding);
  text-align: center;
  color: var(--white);
}

.hero-content {
  max-width: 700px;
  margin: auto;
  font-family: var(--ff-roboto);
}

.hero-title {
  font-size: var(--fs-2);
  font-weight: var(--fw-700);
  margin-bottom: 25px;
  text-shadow: 2px 2px 10px var(--black);
}

.hero-highlight {
  color: var(--raw-seinna);
}

.hero-description {
  font-size: var(--fs-5);
  line-height: 1.8;
  margin-bottom: 30px;
  text-shadow: 1px 1px 5px var(--black);
  font-weight: var(--fw-400);
}



/* In your main CSS file */
#particles-js {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: -1;
  pointer-events: none;
}


.skills-container {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  justify-content: center;
  align-items: center;
}

.skill-icon {
  width: 80px;
  height: 80px;
  object-fit: contain;
}


<!-- CSS -->
<style>
  #hero-heading {
    font-size: clamp(2.5rem, 6vw, 4.5rem);
    margin-bottom: 15px;
    color: #00bfff;
    text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.8);
    max-width: 100vw;
    text-align: center;
    white-space: nowrap; /* Prevent wrapping */
    overflow: hidden;
    text-overflow: ellipsis;
  }

  #hero-heading .highlight {
    color: #fbb034;
  }
</style>
<!-- /* Optional: Remove wrapping on all screen sizes */
@media (max-width: 768px) {
  #hero-heading {
    white-space: nowrap;
    overflow: auto;
  }
} -->

</style>

