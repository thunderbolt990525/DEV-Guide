<template lang="pug">
.welcome
  main
    h1.text-black.font-bold.text-xl.mb-2 What is&nbsp;
      span 💎 DevGuide?
    p DevGuide is a goto place for devs and designers to find new resources and more. As a beginner, it's sometimes not easy to find what you need since you don't know where to look for what.
    p Therefore we created this project to have the most common and best resources for beginners and veterans in one place — kind of like a bookmarks list for devs and designers, containing only the best gems out there.
    p If you want to add your gem, go ahead and open a pull request on GitHub (click on that octocat at the top right corner).
    p By the way, this project lives by getting shared; if you find this worthy, please share it with others.
    
    p.muted // made with love by
    p.contributors class&nbsp;
      a(href="https://twitter.com/thunderbolt") @thunderbolt&nbsp;
      span extends;


</template>

<style lang="scss" scoped>
.welcome {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.muted {
  font-size: 0.8rem;
  opacity: 0.5;
  margin-top: 3rem;
  margin-bottom: 0;
}

.contributors {
  margin-top: 0;
}

main {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  max-width: 50%;
}

@media (max-width: 800px) {
  main {
    max-width: 90%;
  }
}
</style>

