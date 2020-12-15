<template>
  <div>
    <b-navbar toggleable="lg" type="black" variant="white">
      <div class="brand">She<span class="rose">.</span>Only</div>

      <b-navbar-toggle style="color: black" target="nav-collapse"
        >☰</b-navbar-toggle
      >

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item><router-link to="/">Accueil</router-link></b-nav-item>
          <b-nav-item
            ><router-link to="/produits">produits</router-link></b-nav-item
          >
          <b-nav-item
            ><router-link to="/contact">Contact</router-link></b-nav-item
          >
          <b-nav-item-dropdown>
            <!-- Using 'button-content' slot -->
            <template v-slot:button-content> COMPTE </template>
            <b-dropdown-item href="#">Profil</b-dropdown-item>
            <b-dropdown-item href="#">Déconnexion</b-dropdown-item>
          </b-nav-item-dropdown>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-form>
            <b-form-input
              size="sm"
              class="mr-sm-2"
              placeholder="Recherche"
            ></b-form-input>
            <b-button
              variant=" outline-default"
              size="sm"
              class="my-2 my-sm-0"
              type="submit"
              ><i class="fas fa-search"></i
            ></b-button>
          </b-nav-form>

          <b-nav-item-dropdown text="Langue" right>
            <b-dropdown-item href="#">EN</b-dropdown-item>
            <!--<b-dropdown-item href="#">ES</b-dropdown-item>
            <b-dropdown-item href="#">RU</b-dropdown-item> -->
            <b-dropdown-item href="#">FR</b-dropdown-item>
          </b-nav-item-dropdown>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>
<script>
import {
  BNavbar,
  BNavbarBrand,
  BNavbarToggle,
  BNavbarNav,
} from "bootstrap-vue/esm/components/navbar";
import { BCollapse } from "bootstrap-vue/esm/components/collapse";
import {
  BNavItem,
  BNavItemDropdown,
  BNavForm,
} from "bootstrap-vue/esm/components/nav";
import { BDropdownItem } from "bootstrap-vue/esm/components/dropdown";
import { BFormInput } from "bootstrap-vue/esm/components/form-input";
import { BButton } from "bootstrap-vue/esm/components/button";

export default {
  components: {
    BNavbar,
    BNavbarBrand,
    BNavbarToggle,
    BCollapse,
    BNavbarNav,
    BNavItem,
    BNavItemDropdown,
    BDropdownItem,
    BNavForm,
    BFormInput,
    BButton,
  },
};
</script>
<style>
.navbar-brand {
  font-family: vidaloka;
  font-size: 30px;
  font-weight: 5px;
  text-align: center;
  color: black;
}
</style>
