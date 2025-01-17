---
layout: home

title: SoybeanAdmin
titleTemplate: A fresh and elegant admin template

hero:
  name: SoybeanAdmin
  text: Fresh and elegant
  tagline: Based on Vue3,Vite5,TypeScript and UnoCSS
  image:
    src: /logo.svg
    alt: SoybeanAdmin
  actions:
    - theme: brand
      text: Start
      link: /guide/quick-start
    - theme: alt
      text: Introduction
      link: /guide/intro
    - theme: alt
      text: View on GitHub
      link: https://github.com/soybeanjs/soybean-admin
    - theme: alt
      text: React Version Docs ->
      link: https://react-soybean-docs.ohh-889.com/index-cn

features:
  - icon: 🆕
    title: The latest technology stack popular in the community.
    details: Vue3, Vite5, TypeScript, Pinia, UnoCSS.
  - icon: 🔄
    title: Multi-framework Support
    details: Simultaneously supports Vue3 and React, allowing you to flexibly choose your front-end tech stack.
  - icon: 🎨
    title: Integration of Multiple Component Libraries
    details: Adapts to various component libraries such as Element Plus, Naive UI, Ant Design, and Ant Design Vue to meet diverse UI needs.
  - icon: 🦋
    title: Clean Structure
    details: Use pnpm monorepo, clean and elegant structure, easy to maintain. Very high code specification.
  - icon: 🛠️
    title: TypeScript
    details: Strictly typed, easy for team development and maintenance.
  - icon: 🔩
    title: Theme
    details: Built-in rich theme configuration, easily integrate with UnoCSS.
  - icon: 🔗
    title: File routing System
    details: Automatic, intelligent file routing system.
  - icon: 🔑
    title: Auth Router
    details: Support front-end static routing and back-end dynamic routing.
  - icon: ⚙️
    title: Extended Script Tools
    details: Provides multiple scripting capabilities, including one-click dependency upgrades, automatic generation of ChangeLogs, commit messages, etc., greatly improving development efficiency.
---

<script setup>
import {
  VPTeamPage,
  VPTeamPageTitle,
  VPTeamMembers,
  VPTeamPageSection
} from 'vitepress/theme';

const partners = [
  {
    avatar: '	https://avatars.githubusercontent.com/u/49704545?v=4',
    name: 'Soybean',
    title: 'Author',
    desc: 'Creator of SoybeanJS team and author of SoybeanAdmin.',
    links: [
      { icon: 'github', link: 'https://github.com/honghuangdc' }
    ]
  },
  {
    avatar: '	https://avatars.githubusercontent.com/u/79054161?v=4',
    name: '青菜白玉汤',
    title: 'Front-end development · China',
    desc: 'Responsible for front-end development and maintenance, documentation, community maintenance.',
    links: [
      { icon: 'github', link: 'https://github.com/Azir-11' }
    ]
  },
  {
    avatar: 'https://avatars.githubusercontent.com/u/18189346?v=4',
    name: 'paynezhuang',
    links: [
      { icon: 'github', link: 'https://github.com/paynezhuang' }
    ]
  },
  {
    avatar: '	https://avatars.githubusercontent.com/u/35002714?v=4',
    name: 'fonghehe',
    desc:'Be keen on new technology, explore the application and practice of new technology, and use it in real projects.',
    links: [
      { icon: 'github', link: 'https://github.com/fonghehe' }
    ]
  },
  {
    avatar: 'https://avatars.githubusercontent.com/u/37368500?v=4',
    name: '我问这瓜保熟吗',
    links: [
      { icon: 'github', link: 'https://github.com/ByteByteBrew' }
    ]
  },
  {
    avatar: 'https://avatars.githubusercontent.com/u/43030980?v=4',
    name: 'yanbowen',
    links: [
      { icon: 'github', link: 'https://github.com/yanbowe' }
    ]
  },
  {
    avatar: 'https://avatars.githubusercontent.com/u/53158783?v=4',
    name: 'lisong',
    links: [
      { icon: 'github', link: 'https://github.com/SonyLeo' }
    ]
  },
  {
    avatar: 'https://avatars.githubusercontent.com/u/155351881?v=4',
    name: 'Ohh',
    title: 'Front-end development · zhengzhou',
    links: [
      { icon: 'github', link: 'https://github.com/mufeng889' }
    ]
  },
  {
    avatar: 'https://avatars.githubusercontent.com/u/23544762?s=96&v=4',
    name: '一寸灰',
    title: 'Front-end development · Beijing',
    desc: 'Why not',
    links: [
      { icon: 'github', link: 'https://github.com/skyfeiz' }
    ]
  },
]
</script>

<VPTeamPage>
  <VPTeamPageTitle>
    <template #title>SoybeanJs Team</template>
  </VPTeamPageTitle>
  <VPTeamPageSection>
    <template #members>
      <VPTeamMembers size="small" :members="partners" />
    </template>
  </VPTeamPageSection>
</VPTeamPage>
