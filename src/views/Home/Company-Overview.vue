<template>
  <section>
    <hr>
    <div class="content-container--large text--light content-container">
      <h2 class="text-color--matryx-grey text--bold font-size--medium text-center">
        Matryx is a platform <br> that incentivizes collaborative problem-solving
      </h2>
      <div class="overview">
        <div class="overview__column-1 mobile--order-1">
          <h1 class="text-color--matryx-black">Project Background</h1>
          <p class="text-color--matryx-dark-grey">
            Matryx is a product of Nanome. Nanome seeks to democratize science, engineering, and research using Virtual Reality and blockchain technology. Nanome is the creator of Calcflow, the industry-leading VR mathematics toolkit, and nano-one, a VR interface for nanoscale design and simulation.
          </p>
          <a href="http://matryx.ai/site/wp-content/uploads/2017/08/Matryx-Technical-Whitepaper.pdf" target="_blank">
            <button class="btn-red">Read the Whitepaper</button>
          </a>
        </div>
        <div class="overview__column-2 mobile--order-2 overview__img--1">
          <img src="../../assets/images/video-preview.png" alt="">
        </div>
      </div>
      <div class="overview">
        <div class="overview__column-2 overview__img--2">
          <img src="../../assets/images/video-preview.png" alt="">
        </div>
        <div class="overview__column-1">
          <h1 class="text-color--matryx-black">The Problem</h1>
          <p class="text-color--matryx-dark-grey">
            Solving the world’s hardest problems in silos leads to duplication of effort and redundancy. By providing a global community that encourages and incentivizes the exchange of ideas, time to innovation is greatly reduced while problems are solved at a rate otherwise impossible.
            <br/> <br/>
            Research and engineering efforts are fragmented. Time and money are wasted when different teams work on the same problem without coordination. Recognition and grants go to the last people to work on a problem, ignoring dozens of critical contributors. As such there’s no incentive to cooperate with other teams, and no repository of solved problems.
          </p>
        </div>
      </div>
      <div class="overview">
        <div class="overview__column-1 mobile--order-1">
          <h1 class="text-color--matryx-black">The Matryx Solution</h1>
          <p class="text-color--matryx-dark-grey">
            Matryx’s blockchain-based bounty system provides incentives for collaborative problem solving. Creators are rewarded for contributions with MTX tokens. Anyone can post bounties to Matryx. Participants compete to solve these problems in a tournament.

            <br/> <br/>The winning solution of each round is shared publicly so that new contributors can remix into a new iteration, enabling users to reach the goal faster and more effectively.

            Once a problem is solved, rewards and recognition are given to all winning contributors, not just the last contributor, for fairness and transparency.

          </p>
        </div>
        <div class="overview__column-2 mobile--order-2 overview__img--3">
          <img src="../../assets/images/video-preview.png" alt="">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'CompanyOverview'
}
</script>

<style lang="scss" scoped>
@import '../../assets/css/colors';

  section {
    margin-top: 0px;
  }

  hr {
    max-width: 1400px;
    margin: auto;
  }

  h4 {
    margin-top: 0;
  }

  h2.font-size--large {
    font-size: 46px;
    line-height: 55px;
    margin: 40px 0;
  }

  .content-container--large.content-container {
    padding-top: 40px;
  }

  .pull-left {
    float: left;
  }
  .pull-right {
    float: right;
  }

  .overview {
    display:-webkit-box;display:-ms-flexbox;display:flex;
    justify-content: space-between;
    padding: 30px 0;
    border-bottom: 1px solid $light-purple-border;

    // &__img--1 {
    //   background-image: url('../../assets/images/video-preview.png');
    //   background-size: cover;
    // }
    // &__img--2 {
    //   background-image: url('../../assets/images/video-preview.png');
    //   background-size: cover;
    // }
    // &__img--3 {
    //   background-image: url('../../assets/images/video-preview.png');
    //   background-size: cover;
    // }

    &__column-1,
    &__column-2 {
      width: calc(50% - 40px);

    }
    &__column-1 {
    }
    &__column-2 {

      img {
        width: 100%;
      }
    }
  }

  .btn-red {
    background-color: $white;
    color: $matryx-red;
    border-radius: 25px;
    text-transform: uppercase;

    &:hover {
      background-color: $matryx-red;
      color: $white;
    }
  }

  /*----- MEDIA QUERIESS -----*/
  @media screen and (max-width: 750px) {
    .overview {
      flex-direction: column;

      &__column-1,
      &__column-2 {
        width: 100%;
        float: none;

        img {
          margin-bottom: 30px;
        }
      }
    }
    .mobile--order-1 {
      order: 1;
    }
    .mobile--order-1 {
      order: 2;
    }
  }
</style>
