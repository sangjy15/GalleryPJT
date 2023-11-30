<template>
  <div id="app">
    <header>
      <div>GALLERY PJT</div>
    </header>
    <nav>
      <b-row>
        <b-col lg="2" class="pb-2">
          <b-button variant="primary">Default Button..</b-button>
        </b-col>
        <b-col lg="2" class="pb-2">
          <b-button variant="outline-primary">Default Button</b-button>
        </b-col>
        <b-col lg="2" class="pb-2">
          <b-button variant="outline-primary">Default Button</b-button>
        </b-col>
      </b-row>
    </nav>
    <div class="container">
      <div class="contents">
        <b-card
          title="Card Title"
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 20rem"
          class="mb-2"
        >
          <b-card-text>
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </b-card-text>
          <b-button href="#" variant="primary">Go somewhere</b-button>
        </b-card>
      </div>
      <div class="contents">
        <b-card
          title="Card Title"
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 20rem"
          class="mb-2"
        >
          <b-card-text>
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </b-card-text>
          <b-button href="#" variant="primary">Go somewhere</b-button>
        </b-card>
      </div>
      <div class="contents">
        <b-card
          title="Card Title"
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 20rem"
          class="mb-2"
        >
          <b-card-text>
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </b-card-text>
          <b-button href="#" variant="primary">Go somewhere</b-button>
        </b-card>
      </div>
    </div>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin: auto;
  width: 1200px;
}

header {
  width: 100%;
  height: 150px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.container .contents {
  float: left;
  padding: 20px;
}
footer {
  width: 100%;
  height: 150px;
  background: #a2abfc;
  clear: both;
}
</style>
