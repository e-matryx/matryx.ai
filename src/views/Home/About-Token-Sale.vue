<template>
  <section>
    <!-- I'm Dominique now.-->
    <div class="content-container--large content-container">
      <h1 class="text-color--matryx-grey font-size--large text--left">ABOUT OUR TOKEN SALE</h1>
      <div class="card-container--horizontal">
        <div class="about-container card-container--vertical">
          <div class="card">
            <h2 class="text-color--matryx-black">Why do a Token Sale?</h2>
            <p class="text-color--matryx-dark-grey">
              The ultimate goal of Matryx is to incentivize collaboration in fields of knowledge and creation like STEM. To reach that goal, we need resources that support R&#38;D demands and help create a community of participants and contributors. Token Sales have quickly become a proven means to achieve such growth for blockchain-based technologies like Matryx.
            </p>
          </div>
          <div class="card">
            <h2 class="text-color--matryx-black">Why do we need a Blockchain?</h2>
            <p class="text-color--matryx-dark-grey">
              Utilizing blockchain-based bounties, Matryx enables users to validate each participant's contribution to a solution and reward them with MTX tokens. Using a token enables us to leverage smart contract systems, upgrade over time, and gives us the flexibility to shape the platform to the needs of the users.
            </p>
          </div>
          <div class="card">
            <h2 class="text-color--matryx-black">What are the benefits? </h2>
            <p class="text-color--matryx-dark-grey">
              Smart contracts reduce the friction of tracking and compensating contributors. Each round of a bounty competition, the winners are rewarded, and a new generation of children is created. All fiterations are managed by the tournament contracts. The provenance of an idea or work can be easily tracked and can be rewarded fairly and publicly.
            </p>
          </div>
        </div>
        <div class="roadmap-container card-container--vertical">
          <div class="roadmap">
            <h2 class="text-color--matryx-black">ROADMAP</h2>
            <h3 class="roadmap__year text-color--grey">2017</h3>
            <div class="roadmap__section ">
              <div class="roadmap__section__quarter roadmap__section__quarter--past ">Q2</div>
              <p class="roadmap__section__date roadmap__section__date--past">JUN 2017</p>
              <div class="roadmap__section__description text-color--matryx-dark-grey">
                <p>White Paper &#38; Token Sale Announcement</p>
                <caption>Token Pre-Sale Launches at 10am GMT for purchases of over 150 ETH. Pre-sale period will remain open for one week from Sept. 6 to Sept 13.
                </caption>
              </div>
            </div>
            <h3 class="roadmap__year text-color--grey">2017</h3>
            <div class="roadmap__section ">
              <div class="roadmap__section__quarter roadmap__section__quarter--future">Q3</div>
              <p class="roadmap__section__date roadmap__section__date--future">SEPT 2017</p>
              <div class="roadmap__section__description text-color--matryx-dark-grey">
                <p>Token Sale Launch</p>
                <caption>User acquisition focused primarily on Universities and academia, building small and dedicated community of users.
                </caption>
              </div>
            </div>
            <h3 class="roadmap__year text-color--grey">2018</h3>
            <div class="roadmap__section ">
              <div class="roadmap__section__quarter roadmap__section__quarter--future">Q1</div>
              <p class="roadmap__section__date roadmap__section__date--future">MAR 2018</p>
              <div class="roadmap__section__description text-color--matryx-dark-grey">
                <p>Marketplace Alpha Testnet</p>
                <caption>Working MVP for public use. Expand focus to research and model a variety of attribution solutions.
                </caption>
              </div>
            </div>
            <div class="roadmap__section ">
              <div class="roadmap__section__quarter roadmap__section__quarter--future">Q2</div>
              <p class="roadmap__section__date roadmap__section__date--future">JUN 2018</p>
              <div class="roadmap__section__description text-color--matryx-dark-grey">
                <p>Marketplace Beta Testnet</p>
                <caption>Centralized tests of implemented systems. Create decentralized reputation board, identifying users and their contributions.
                </caption>
              </div>
            </div>
            <div class="roadmap__section ">
              <div class="roadmap__section__quarter roadmap__section__quarter--future">Q4</div>
              <p class="roadmap__section__date roadmap__section__date--future">NOV 2018</p>
              <div class="roadmap__section__description text-color--matryx-dark-grey">
                <p>Marketplace Beta Mainnet</p>
                <caption>Expand user base to tens of thousands. Cultivate economy of practical/ less academic bounties.
                </caption>
              </div>
            </div>
            <h3 class="roadmap__year text-color--grey">2019</h3>
            <div class="roadmap__section ">
              <div class="roadmap__section__quarter roadmap__section__quarter--future">Q2</div>
              <p class="roadmap__section__date roadmap__section__date--future">JUN 2019</p>
              <div class="roadmap__section__description text-color--matryx-dark-grey">
                <p>Marketplace Public Launch</p>
                <caption>Begin to decentralize storage solutions and narrow down attribution + reputation systems.
                </caption>
              </div>
            </div>
            <h3 class="roadmap__year text-color--grey">2020</h3>
            <div class="roadmap__section ">
              <div class="roadmap__section__quarter roadmap__section__quarter--future">Q4</div>
              <p class="roadmap__section__date roadmap__section__date--future">NOV 2020</p>
              <div class="roadmap__section__description text-color--matryx-dark-grey">
                <p>Decentralized Reputation &#38; Storage</p>
                <caption>Begin to decentralize storage solutions and narrow down attribution + reputation systems.
                </caption>
              </div>
            </div>
          </div>
         </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutTokenSale'
}
</script>

<style lang="scss" scoped>
@import '../../assets/css/colors';
  .card-container {
    &--horizontal,
    &--vertical {
      display:-webkit-box;display:-ms-flexbox;display:flex;
      -webkit-box-pack: justify;
      -ms-flex-pack: justify;
      justify-content: space-between;
    }
    &--vertical {
      -webkit-box-orient: vertical;
      -webkit-box-direction: normal;
      -ms-flex-flow: column;
      flex-flow: column;

      &.about-container > * {
        height: calc(33.3333% - 10px);
      }
    }
    &--horizontal {
      margin-top: 40px;

      & > * {
        width: calc(50% - 10px);
      }
    }
  }
  .card {
    display: -webkit-box; display: -ms-flexbox;display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-flow: column;
    flex-flow: column;
    border: 1px solid $light-purple-border;
    border-radius: 0;
    padding: 20px;
    -webkit-box-pack: start;
    -ms-flex-pack: start;
    justify-content: flex-start;

    h2, p {
      -webkit-box-flex: 0;
      -ms-flex: 0 1 auto;
      flex: 0 1 auto;
    }

    img {
      height: auto;
      width: 100%;
    }
  }



  .roadmap {
    max-width: 300px;
    width: 100%;
    margin: 0 0 0 auto;
    right: 20px;
    position: relative;

    h2 {
      position: relative;
      right: 60px;
    }
    h3 {
      position: relative;
      right: 30px;
    }

    &__section {
      position:relative;
      border-left: 1px solid $classic-grey;
      display:-webkit-box;display:-ms-flexbox;display:flex;

      &:last-child {
        border-left: none;
      }

      & > * {

      }

      &__date {
        display: inline-block;
        font-size: 12px;
        text-transform: uppercase;
        flex: 0 1 0;
        min-width: 80px;
        position: relative;
        left: 30px;

        &--future { color: $matryx-blue; }
        &--past { color: $classic-grey;}
      }

      &__quarter {
        background-color: #80828D;
        border: 3px solid white;
        color: rgba(255, 255, 255, 0.7);
        display: inline-block;
        border-radius: 50px;
        padding: 2px 2px 2px 2px;
        height: 34px;
        width: 34px;
        text-align: center;
        position: absolute;
        left: -17px;

          &--future { background-color: $matryx-blue; color: rgba(255,255,255,0.7);}
          &--past { background-color: $classic-grey;color: rgba(255,255,255,0.7);}
      }

      &__description {
        position: relative;
        left: 20px;

        p {
          font-size: 18px;
          margin: 0;
        }
        caption {
          padding: 0;
          display: inline-block;
          font-style:normal;
        }
      }

    }
  }
  /*----- MEDIA QUERIESS -----*/
  @media screen and (max-width: 850px) {
    .card-container {
      &--vertical {
        width: 100%;
      }
      &--horizontal {
        flex-flow:column;
        width: 100%;
        & > * {
          width:100%;
        }
      }
    }
    .card {
      margin-bottom: 20px;
    }
    .roadmap {
      width:calc(100% - 80px);
      max-width: 500px;
      margin: 0 auto;

      h2 {
        text-align: center;
        right: 0;
      }
    }
  }
</style>
