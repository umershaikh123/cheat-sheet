

# FrameWorks/ Libraries
Full guide on important Css frameworks :
https://www.youtube.com/watch?v=CQuTF-bkOgc


- ## Tailwind css
Link : https://tailwindcss.com/docs/guides/nextjs
cheatsheet : https://nerdcave.com/tailwind-cheat-sheet
- ## Saas

Link : https://sass-lang.com/
- ## Headless UI

Link : https://headlessui.com/

- ## Daisy UI
Link : https://daisyui.com/
- ## Material UI
Link : https://mui.com/material-ui/getting-started/overview/


## React Animation libraries
- Anime.js : https://animejs.com/
- Framer Motion : https://www.framer.com/motion/
- React spring : https://www.react-spring.dev/docs/getting-started
- React reveal : https://www.react-reveal.com/examples/
- React awesome reveal : https://react-awesome-reveal.morello.dev/
- 3d effects library : https://threejs.org/

# css cheatsheet

### Clamp

```
Clamp(min , preferred , max);
width : Clamp(200px , 50% , 400px);
width : Clamp(45ch , 50% , 75ch);

```

### Aspect Ratio

```
aspect ratio: 16/9

```

### Variables


```
:root {

    --variable-Name: rgb(0,0,0);
} 


p {
    color : var(--variable-Name);
}

h {
    --variable-Name : green ; //override variable 
    color : var(--variable-Name);
}


```


### calc()

```

width : calc(100vh - 200px)
width : calc(100vh + 200px)
width : calc(100vh * 200px)
animation-delay : calc(var(--order * 100 ms))

```

### order
```
"--order : 1"
"--order : 2"
"--order : 3"
```

