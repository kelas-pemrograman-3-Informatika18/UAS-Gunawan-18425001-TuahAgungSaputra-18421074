<template>
  <q-page padding class="bg-blue-5 glossy">
    <div class="q-pa-md row items-start q-gutter-md">
    <q-card
      class="my-card text-white"
      style="background: transparent"
      flat
    >
      <q-card-section>
        <div class="text-h6">Tentang Aplikasi</div>
        <div class="text-subtitle2">E-Computer</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        {{ tentang }}
      </q-card-section>
      <div class="q-pa-md row items-start q-gutter-md">
      </div>
    </q-card>
    </div>
  </q-page>
</template>
<script>
export default {
  data () {
    return {
      tentang: 'E-Computer merupakan aplikasi yang digunakan untuk memesan laptop dan komputer dengan kualitas HD dan dikirimkan serta diantar ke customer dengan baik '
    }
  }
}
</script>
