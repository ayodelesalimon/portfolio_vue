<template>
        
   <div id="portfolio-project">
       
      <b-container class="bv-example-row">
        <b-row>
          <b-col
            ><div>
              <b-card
                title="Card Title"
                img-src="https://picsum.photos/600/300/?image=25"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem;"
                class="mb-2"
              >
                <b-card-text>
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </b-card-text>

                <b-button variant="outline-secondary">JAVA</b-button>
                <b-button variant="outline-secondary">MYSQL</b-button>
              </b-card>
            </div>
          </b-col>
          <b-col
            ><div>
              <b-card
                title="Card Title"
                img-src="https://picsum.photos/600/300/?image=25"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem;"
                class="mb-2"
              >
                <b-card-text>
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </b-card-text>

                <b-button variant="outline-secondary">FLUTTER</b-button>
              </b-card>
            </div>
          </b-col>
          <b-col
            ><div>
              <b-card
                title="Card Title"
                img-src="https://picsum.photos/600/300/?image=25"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem;"
                class="mb-2"
              >
                <b-card-text>
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </b-card-text>

                <b-button variant="outline-secondary">VUE</b-button>
              </b-card>
            </div>
          </b-col>
        </b-row>
      </b-container>

      <b-container class="bv-example-row">
        <b-row>
          <b-col
            ><div>
              <b-card
                title="Card Title"
                img-src="https://picsum.photos/600/300/?image=25"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem;"
                class="mb-2"
              >
                <b-card-text>
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </b-card-text>

                <b-button variant="outline-secondary">JAVA</b-button>
                <b-button variant="outline-secondary">MYSQL</b-button>
              </b-card>
            </div>
          </b-col>
          <b-col
            ><div>
              <b-card
                title="Card Title"
                img-src="https://picsum.photos/600/300/?image=25"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem;"
                class="mb-2"
              >
                <b-card-text>
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </b-card-text>

                <b-button variant="outline-secondary">FLUTTER</b-button>
              </b-card>
            </div>
          </b-col>
          <b-col
            ><div>
              <b-card
                title="Card Title"
                img-src="https://picsum.photos/600/300/?image=25"
                img-alt="Image"
                img-top
                tag="article"
                style="max-width: 20rem;"
                class="mb-2"
              >
                <b-card-text>
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </b-card-text>

                <b-button variant="outline-secondary">VUE</b-button>
              </b-card>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

.container{
   
    display: flex;
}
/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
  .col {
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .col {
    flex: 100%;
    max-width: 100%;
  }
}
</style>