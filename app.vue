<template>
  <div>
    <section>
      <nav class="menu">
        <ul class="flex">
          <li>
           <span>icon</span>
           <span>6666 7777</span>
          </li>
          <li>
            <span>icon</span>
            <span>6666 7777</span>
          </li>
        </ul>
        <ul class="flex">
          <li class="menu-item">facebook</li>
          <li class="menu-item">youtube</li>
        </ul>
      </nav>
    </section>
  </div>
</template>
<style>
.menu {
  display: grid;
  grid-template-columns: 1fr 1fr;
}
.flex {
  display: flex;
  gap: 10px;
}
.menu-item{
  background-color: #f0f0f099;
  padding: 2px 5px;
  border-radius: 10px;
}
.menu-item:hover{
  background-color: rgb(183, 21, 48);
  color: black;
  border: 2px solid #08949c;
}

</style>
