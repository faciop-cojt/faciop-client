<template>
  <header>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand to="/">
        <img class="logo" src="../assets/logo_transparent_fix.png" />
      </b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item to="/goods">商品一覧</b-nav-item>
          <b-nav-item to="/about">このサイトについて</b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <!-- <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
          <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
        </b-nav-form> -->

          <b-nav-item-dropdown text="ユーザー" right>
            <b-dropdown-item href="/profile">プロフィール</b-dropdown-item>
            <b-dropdown-item href="/logout">ログアウト</b-dropdown-item>
          </b-nav-item-dropdown>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </header>
</template>

<style>
.logo {
  width: 100px;
}
</style>
