<template>
  <nav>
    <div class="links">
      <ul class="UpperLinks">
        <li>SHOP</li>
      </ul>
    </div>
    <div class="group">
      <div class="line">
      </div>
      <div class="SubLinks">
        <ul class="SubLinkGroup">
          <li>Birthdays</li>
          <li>Birth Announcements</li>
          <li>Graduations</li>
          <li>Showers</li>
          <li>Milestones</li>
          <li>Holidays</li>
        </ul>
      </div>
    </div>
    <div>
      <ul class="LowerLinks">
        <li>INSTALLATION GUIDE</li>
        <li>CONTACT</li>
        <li>FAQ</li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "SideNav"
}
</script>

<style scoped>
@import url("https://use.typekit.net/ijl4xlv.css");
nav {
  display: flex;
  flex-direction: column;
  margin-top: 0;
  position: fixed;
  left: auto;
  right: auto;
  top: 0;
  bottom: 0;
  width: 250px;
  height: 100vh;
  background-color: #fff;
  border-style: none solid none none;
  border-width: 0 1px 0 0;
  border-color: #757472;
  z-index: 9;
  text-align: left;
  font-family: proxima-nova,sans-serif;
  color: #757472;
}

.links {
  margin-top: 100px;
}

ul {
  list-style: none;
}

li:hover {
  text-decoration: underline;
}

.group {
  display: flex;
  flex-direction: row;
  margin-left: auto;
  margin-right: auto;
  align-items: center;
  justify-content: center;
}

.line {
  width: 1px;
  height: 85%;
  background-color: #757472;
  margin-left: 3px;
  margin-right: -20px;
}

.SubLinks {
  margin-left: 0;
  margin-right: auto;
  cursor: pointer;
}

.UpperLinks {
  margin-bottom: -5px;
  font-weight: 400;
  font-size: 18px;
  cursor: pointer;
}

.SubLinkGroup {
  line-height: 40px;
  font-weight: 300;
  font-size: 16px;
  cursor: pointer;
}

.LowerLinks {
  margin-top: -5px;
  line-height: 40px;
  font-weight: 400;
  font-size: 18px;
  cursor: pointer;
}
</style>
