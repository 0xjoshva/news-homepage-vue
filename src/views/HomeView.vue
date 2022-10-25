<template>
  <section>
    <div class="container">
      <div class="left">
        <img src="../assets/image-web-3-desktop.jpg" alt="" id="image" />
        <div class="text">
          <h3>The Bright Future of Web 3.0?</h3>
          <div class="para">
            <p>
              We dive into the next evolution of the web that claims to put the
              power of the platforms back into the hands of the people. But is
              it really fulfilling its promise?
            </p>
            <button class="readmore-btn">READ MORE</button>
          </div>
        </div>
      </div>
      <div class="right">
        <h3 id="header">New</h3>
        <div>
          <div class="article">
            <h5 class="headline">Hydrogen VS Electric Cars</h5>
            <p class="blurb">
              Will hydrogen-fueled cars ever catch up <br />
              to EVs?
            </p>
          </div>
          <div class="article">
            <h5 class="headline">The Downsides of AI Artistry</h5>
            <p class="blurb">
              What are the possible adverse effects of <br />
              on-demand AI image generation?
            </p>
          </div>
          <div class="article">
            <h5 class="headline">Is VC Funding Drying Up?</h5>
            <p class="blurb">
              Private funding by VC firms is down 50% <br />
              YOY. We take a look at what that means.
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="wrapper">
      <div class="item">
        <img src="../assets/image-retro-pcs.jpg" alt="" />
        <div class="content">
          <h3>01</h3>
          <h4>Reviving Retro PCs</h4>
          <p>
            What happens when old PCs <br />
            are given modern upgrades?
          </p>
        </div>
      </div>
      <div class="item">
        <img src="../assets/image-top-laptops.jpg" alt="" />
        <div class="content">
          <h3>02</h3>
          <h4>Top 10 Laptops of 2022</h4>
          <p>
            Our best picks for various <br />
            needs and budgets.
          </p>
        </div>
      </div>
      <div class="item">
        <img src="../assets/image-gaming-growth.jpg" alt="" />
        <div class="content">
          <h3>03</h3>
          <h4>The Growth of Gaming</h4>
          <p>
            How the pandemic has sparked <br />
            fresh opportunities.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>
<style scoped>
section {
  width: 100%;
  height: fit-content;
  background: var(--bg);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  row-gap: 5rem;
}
.container {
  width: 60%;
  height: fit-content;
  display: flex;
  column-gap: 2rem;
}
.left {
  width: 50rem;
  height: fit-content;
}
#image {
  width: 100%;
  height: 20rem;
  object-fit: cover;
}
.text {
  padding-top: 2rem;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: flex-start;
  column-gap: 4rem;
  padding-right: 1rem;
}
.text h3 {
  font-weight: 800;
  font-family: "Inter";
  font-size: 3.5rem;
  line-height: 3.8rem;
  color: var(--verydarkblue);
}
.text p {
  font-size: 15px;
  font-family: "Inter";
  font-weight: 400;
  line-height: 1.7rem;
  color: var(--darkgrayblue);
}
.text button {
  background: var(--softred);
  color: var(--bg);
  font-family: "Inter";
  font-weight: 600;
  font-size: 1rem;
  letter-spacing: 4px;
  border: none;
  padding: 0.8rem 1.6rem;
  width: fit-content;
  display: flex;
  justify-self: end;
}
.para {
  display: flex;
  flex-direction: column;
  row-gap: 2.7rem;
}
.right {
  padding-left: 2rem;
  padding-right: 2rem;
  padding-top: 2rem;
  width: 33%;
  background: var(--verydarkblue);
  color: white;
  font-family: "Inter";
  padding-bottom: none !important;
}
#header {
  font-size: 2.5rem;
  font-family: "Inter";
  padding-bottom: 1rem;
  color: var(--softorange);
}
.headline {
  color: var(--bg);
  font-size: 1.3rem;
  font-weight: 700;
  padding-bottom: 0.5rem;
}
.blurb {
  color: var(--grayishblue);
}
.article {
  padding-bottom: 2rem;
  border-bottom: 1px solid var(--darkgrayblue);
  margin-bottom: 2rem;
}
.article:nth-last-of-type(1) {
  border-bottom: none;
  padding-bottom: 0;
  margin-bottom: 0;
}
.wrapper {
  width: 60%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.item {
  display: flex;
  column-gap: 1.5rem;
}
.item img {
  height: 8rem;
}
.content{
 display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
    height: 8rem;
    font-family: 'Inter';
}
.content h3{
  font-size: 2rem;
  
  color: var(--grayishblue);
  font-weight: 700;
  line-height: 1.6rem;
}
.content h4{
font-size: 1.2rem;
font-weight: 800;
color: var(--verydarkblue);
}
.content{
  color: var(--darkgrayblue);
}
</style>
