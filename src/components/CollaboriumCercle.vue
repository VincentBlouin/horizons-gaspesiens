<template>
  <Cercle
      title="Collaborium et espace de vie"
      anchor="collaborium"
      image="travailler au LL.jpg"
  >
    <div slot="subtitle">
      Central, flexible, collectif, le Collaborium est l'espace-temps de
      collaboration, terme francisé pour "Coworking space".
    </div>
    <div slot="content">
      <p class="">
        Accès à un espace de travail avec internet
        <v-icon>wifi</v-icon>
        , machine à café
        <v-icon>fa-coffee</v-icon>
        , cuisine pour vous faire à manger
        <v-icon>fastfood</v-icon>
        , divans
        <v-icon>fa-couch</v-icon>
        pour relaxer, autres travailleurs et travailleuses autonomes avec qui
        échanger (ou vous pouvez apporter vos écouteurs pour créer votre
        espace perso), table de ping pong
        <v-icon>fa-table-tennis</v-icon>
        et babyfoot pour se changer les idées: le Collaborium au Loco Local
        c'est tout ça et bien plus encore!
      </p>
      <p>Venez l'essayer!</p>
    </div>
  </Cercle>
</template>

<script>
export default {
  name: "CollaboriumCercle",
  components: {
    Cercle: () => import("@/components/Cercle")
  },
}
</script>

<style scoped>

</style>