<template>
  <header class="hero">
    <img class="hero-image" src="/wine-hero.webp" />
    <nav class="navigation">
      <section class="primary-navigation">
        <h1>WineFlix</h1>
        <ul class="navigation-links">
          <li
            v-for="navigationLink in navigationLinks"
            :key="navigationLink.label"
            :class="{ active: navigationLink.isActive }"
          >
            <NavigationLink
              :url="navigationLink.url"
              :label="navigationLink.label"
            />
          </li>
        </ul>
      </section>
      <section class="secondary-navigation">
        <Avatar :letter="avatarData.letter" :url="avatarData.url" />
      </section>
    </nav>
    <Hero
      :imageUrl="heroData.imageUrl"
      :title="heroData.title"
      :subtitle="heroData.subtitle"
      :description="heroData.description"
    />
  </header>
</template>

<script>
import Hero from '@/components/Hero.vue';
import NavigationLink from '@/components/NavigationLink.vue';
import Avatar from '@/components/Avatar.vue';

export default {
  name: 'Header',
  components: {
    Hero,
    NavigationLink,
    Avatar,
  },
  computed: {
    navigationLinks() {
      return [
        {
          label: 'Home',
          url: '#',
          isActive: true,
        },
        {
          label: 'Whites',
          url: '#',
          isActive: false,
        },
        {
          label: 'Reds',
          url: '#',
          isActive: false,
        },
        {
          label: 'Blends',
          url: '#',
          isActive: false,
        },
      ];
    },
    avatarData() {
      return {
        letter: 'P',
        url: '#',
      };
    },
    heroData() {
      return {
        title: 'Rex Goliath',
        subtitle: 'His Royal Majesty is back.',
        imageUrl: '/rex-goliath-logo.png',
        description: `America's most unhinged rooster is out of retirement, and this time? He's mad
  as hell.  Experience the unapologetic flavor burst of Rex Goliath.`,
      };
    },
  },
};
</script>
