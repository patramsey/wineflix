<template>
  <div class="hero-content">
    <h2>
      <img :alt="title" :src="imageUrl" />
    </h2>
    <h3>{{ subtitle }}</h3>
    <p>
      {{ description }}
    </p>
    <ul class="controls">
      <li>
        <button class="primary-action">
          <FontAwesomeIcon icon="play" />
          <span>Drink</span>
        </button>
      </li>
      <li>
        <button class="secondary-action">
          <FontAwesomeIcon icon="info-circle" />
          <span>More Info</span>
        </button>
      </li>
    </ul>
  </div>
</template>

<script>
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';

export default {
  name: 'Hero',
  components: {
    FontAwesomeIcon,
  },
  props: {
    imgAlt: String,
    imageUrl: String,
    title: String,
    description: String,
    subtitle: String,
  },
};
</script>
