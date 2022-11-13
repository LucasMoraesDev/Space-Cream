<main>
# Space-Cream

<a href="https://codepen.io/lucasmoraesdev/full/yLEMjPP">Visite a página!</a>

  <div >
  <article>
    <img  class="first"src="Screenshot_full.png">
    <img class="tablet"src="Screenshot_tablet.png">
  </article>

  <sidebar>
    <img class="mobile"src="Screenshot_mobile.png">
  </sidebar>

  </div>
</main>

<style>
div{
  display:flex;
  flex-direction: row;

}

article{
  display:flex;
  flex-direction: column;
}

.first{
  grid-area: first;
  width: 60%;
}
.mobile{
  grid-area: mobile;
   width: 100%;
}
.tablet{
  grid-area: tablet;
  width: 60%;
}
</style>
