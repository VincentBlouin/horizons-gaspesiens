<template>
  <Cercle
      title="Groupe d'achat"
      anchor="groupe-achat"
      image="groupe-achat.jpg"
  >
    <!--https://pixabay.com/fr/haricots-assortiment-agriculture-3861864/-->
    <div slot="subtitle">
      Commander des produits biologiques, locaux, en grand format pour limiter
      la quantité d'emballage, et acheter ensemble pour réduire le coût
      d'achat et augmenter la diversité et l'accessibilité d'une nourriture
      saine et responsable.
    </div>
    <div slot="content">
      <p>
        Manger devient alors un moyen de constuire une communauté durable et
        autonome, saine et solidaire.
      </p>
      <v-card class="mt-6">
        <v-list>
          <v-list-item
              href="mailto:groupe.achat.hg@gmail.com,she_know@hotmail.com"
          >
            <v-list-item-action>
              <v-icon>mail</v-icon>
            </v-list-item-action>
            <v-list-item-title class="body-1">
              Demande d'adhésion à groupe.achat.hg@gmail.com
            </v-list-item-title>
          </v-list-item>
          <v-list-item href="https://foodclub.org/bonaventure">
            <v-list-item-action>
              <v-icon>fa-clipboard-list</v-icon>
            </v-list-item-action>
            <v-list-item-title class="body-1">
              Logiciel de commande
            </v-list-item-title>
          </v-list-item>
          <v-list-item
              href="http://horizonsgaspesiens.net/sites/default/files/Compte-rendu_2018-01-17_0.pdf"
          >
            <v-list-item-action>
              <v-icon>picture_as_pdf</v-icon>
            </v-list-item-action>
            <v-list-item-title class="body-1">
              Compte rendu de réunion
            </v-list-item-title>
          </v-list-item>
        </v-list>
      </v-card>
    </div>
  </Cercle>
</template>

<script>
export default {
  name: "GroupeAchatCercle",
  components: {
    Cercle: () => import("@/components/Cercle")
  },
}
</script>

<style scoped>

</style>