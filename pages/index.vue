<template>
  <div>
    <div>
      <b-jumbotron header="Lubbock Bartender" lead="Let us take the hassle out of your event">
        <p>For more information, or to contact us about your next event, please click below!</p>
        <b-button variant="primary" href="#">
          Learn More
        </b-button>
      </b-jumbotron>
    </div>
    <b-container>
      <b-card img-src="https://placekitten.com/300/300" img-alt="Card image" img-left class="mb-3">
        <b-card-text>
          Some quick example text to build on the card and make up the bulk of the card's content.
        </b-card-text>
      </b-card>

      <b-card img-src="https://placekitten.com/300/300" img-alt="Card image" img-right>
        <b-card-text>
          Some quick example text to build on the card and make up the bulk of the card's content.
        </b-card-text>
      </b-card>
    </b-container>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  data () {
    return {
      test: 'FARTS'
    }
  },
  computed: {
    anotherTest () {
      return `COMPUTED ${this.test}`
    }
  }
}
</script>
