<script setup lang="ts"></script>

<template>
  <WelcomeItem>
    <template #icon>
      <IconHtml />
    </template>
    <template #heading>HTML</template>
    <RouterLink to="/vue">HTML playground</RouterLink>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconCss />
    </template>
    <template #heading>CSS</template>
    <RouterLink to="/vue">CSS playground</RouterLink>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconVuejs />
    </template>
    <template #heading>Vue</template>
    <RouterLink to="/vue">Vue playground</RouterLink>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconJavascript />
    </template>
    <template #heading>Javascript</template>
    <RouterLink to="/typescript">Javascript playground</RouterLink>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconTypescript />
    </template>
    <template #heading>TypeScript</template>
    <RouterLink to="/typescript">TypeScript playground</RouterLink>
  </WelcomeItem>
</template>
