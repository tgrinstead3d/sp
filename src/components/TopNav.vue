<template>
  <nav>
    <div class="NavWrapper">
      <div class="Left">
        <div class="Logo">
          <img src="../assets/splogo.png" alt="#">
        </div>
        <div class="Search">
          <div class="SearchIcon">
            <img src="../assets/searchIcon.png" alt="#">
          </div>
          <div class="SearchBox">
            <span id="TempSearch">Search Placeholder</span>
          </div>
        </div>
      </div>
      <div class="Right">
        <div class="Cart">
          <h3>CART</h3>
          <div class="CartBubble">
            <span>0</span>
          </div>
        </div>
        <div class="MobileNav">
          <p>Test</p>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "TopNav"
}
</script>

<style scoped>
.NavWrapper {
  display: flex;
  flex-direction: row;
  margin-inline: auto;
  width: 1920px;
  height: 80px;
  align-items: center;
}
nav {
  display: flex;
  flex-direction: row;
  margin-inline: auto;
  height: 80px;
  width: 100vw;
  background-color: #fff;
  border-style: none none solid none;
  border-width: 0 0 1px 0;
  border-color: #757472;
  z-index: 10;
  font-family: proxima-nova,sans-serif;
  color: #757472;
  position: fixed;
  top: 0;
  left: 0;
}
.Logo {
  display: flex;
  width: 250px;
  margin-inline: auto;
  justify-content: center;
  align-items: center;
}
.Left {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  margin-left: 0;
  margin-right: auto;
}
.Search {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin-left: 1rem;
  margin-right: auto;
}
.SearchIcon {
  padding-top: 5px;
  margin-right: .5rem;
}
.Right {
  display: flex;
  flex-direction: row;
  margin-right: 0;
  margin-left: auto;
  padding-right: 1rem;
}
.Cart {
  display: flex;
  flex-direction: row;
  margin-left: auto;
  margin-right: 0;
  align-items: center;
}
h3 {
  font-size: 18px;
  font-weight: 400;
}
.CartBubble {
  display: flex;
  width: 23px;
  height: 23px;
  border-radius: 100%;
  background-color: #757472;
  color: white;
  align-items: center;
  justify-content: center;
  font-size: 16px;
  font-weight: 400;
  margin-left: .5rem;
}
#TempSearch {
  display: flex;
  opacity: .5;
}

.MobileNav {
  display: none;
}
</style>
