<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <div class="q-pa-md q-gutter-y-sm">

    <div class=" text-white">
      <q-toolbar>

        <q-btn color="accent" icon="manage_accounts" label="Login" />

        <q-space />

        <q-btn flat round dense icon="shopping_cart" class="q-mr-xs" />
      </q-toolbar>

      <q-toolbar inset>

        <div class="q-mr-xs" style="margin-top: 10px">
        <q-img src="../../public/images/logo.png" width="150px" />
      </div>

        <q-breadcrumbs active-color="accent" style="color: #8257e6" class="absolute-center text-h5">
          <q-breadcrumbs-el label="Home" icon="home" />
          <q-breadcrumbs-el label="Sobre" icon="fingerprint" />
          <q-breadcrumbs-el label="Produtos" icon="book" />
          <q-breadcrumbs-el label="Contato" icon="phone" />
        </q-breadcrumbs>
      </q-toolbar>
    </div>
  </div>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>

export default {
  name: 'MainLayout',
  data () {
    return {}
  }
}
</script>
import {
  Quasar,
  QToolbar,
  QToolbarTitle,
  QBtn,
  QImg
} from 'quasar'
