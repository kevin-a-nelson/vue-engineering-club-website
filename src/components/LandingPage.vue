<template>
  <div id="landing-page">
    <div id="top-section">
      <div id="top-section-container">
        <h1 type="info" id="top-section-title">Stolaf & Carlton Engineering Club</h1>
        <span >Can we build it? Yes we can!</span>
        <div id="top-section-btns">
          <div id="join-now-container">
            <b-button size="lg" block variant="primary">Join Now</b-button>
          </div>
          <div id="see-more-container">
            <b-button class="see-more-btn" size="lg" block variant="outline-primary" >
              <a href="#projects" v-smooth-scroll>See More</a>
            </b-button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  name: 'landing-page'
  export default {
    data() {
      return {
        screen: {
          width: 500,
          height: 500
        }
      }
    }
  }
</script>

<style>

.see-more-btn:hover a {
  color: white;
  text-decoration: none;
}

#top-section-title {
  max-width: 300px;
  margin-bottom: 30px;
}


#top-section-container {
  max-width: 1000px;
  margin: 0px auto;
  text-align: left;
  color: white;
}


#top-section {
  padding: 0 50px;
}

#top-section-btns {
  margin-top: 50px;
  display: flex;
}

#join-now-container {
  width: 300px;
  margin-right: 50px;
}

#see-more-container {
  width: 200px;
}

#landing-page {
  padding-top: 200px;
  position: relative;
  background-color: #2d3436;
  background-image: linear-gradient(315deg, #2d3436 0%, #000000 74%);
  background-image: url(https://wallpaperplay.com/walls/full/f/f/5/177539.jpg);
  height: 100%;
  justify-content: center;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}

</style>