<template>
  <div>
    <Nav />
    <div class="h-screen flex">
      <div
        class="
          container
          mx-auto
          px-4
          self-center
          flex
          justify-around
          flex-wrap
          w-3/5
        "
      >
        <div v-for="card in cards" :key="card.img">
          <Card :href="card.href" :img="card.img" :title="card.title" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Nav from "../components/nav.vue";
import Card from "../components/cardHome.vue";
export default {
  components: {
    Nav,
    Card
  },
  data() {
    return {
      cards: [
        { href: "/", img: "/registro-online.png", title: "Registro diario" },
        { href: "/", img: "/historico-medico.png", title: "Histórico" },
        { href: "/", img: "/saude.png", title: "Dicas" },
        { href: "/", img: "/user.png", title: "Seu perfil" }
      ]
    };
  }
};
</script>

<style></style>
