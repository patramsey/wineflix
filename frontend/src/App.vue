<template>
  <Header />
  <main>
    <section class="category">
      <h2>Drink Again</h2>
      <ul>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
            <span class="new-badge">New!</span>
          </div>
        </li>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
          </div>
        </li>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
            <span class="new-badge">New!</span>
          </div>
        </li>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
          </div>
        </li>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
            <span class="new-badge">New!</span>
          </div>
        </li>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
          </div>
        </li>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
          </div>
        </li>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
          </div>
        </li>
      </ul>
    </section>
    <section class="category">
      <h2>Keep Drinking</h2>
      <ul>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
            <div class="amount-consumed">
              <progress min="0" max="100" value="22"></progress>
            </div>
          </div>
        </li>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
            <div class="amount-consumed">
              <progress min="0" max="100" value="22"></progress>
            </div>
          </div>
        </li>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
            <div class="amount-consumed">
              <progress min="0" max="100" value="22"></progress>
            </div>
          </div>
        </li>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
            <div class="amount-consumed">
              <progress min="0" max="100" value="22"></progress>
            </div>
          </div>
        </li>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
            <div class="amount-consumed">
              <progress min="0" max="100" value="22"></progress>
            </div>
          </div>
        </li>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
            <div class="amount-consumed">
              <progress min="0" max="100" value="22"></progress>
            </div>
          </div>
        </li>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
            <div class="amount-consumed">
              <progress min="0" max="100" value="22"></progress>
            </div>
          </div>
        </li>
        <li>
          <div class="wine">
            <img src="/red-wine.jpg" alt="Wine" />
            <div class="amount-consumed">
              <progress min="0" max="100" value="22"></progress>
            </div>
          </div>
        </li>
      </ul>
    </section>
  </main>
</template>

<script>
import Header from '@/components/Header.vue';

export default {
  name: 'App',
  components: {
    Header,
  },
};
</script>

<style lang="scss">
</style>
