<template>
  <div class="event-item">
    <div class="event-item__heading">
      <img class="event-item__heading__img" :src="image">
      <div class="event-item__heading__text">
        <h4 class="event-item__heading__name">{{ name }}</h4>
      </div>
    </div>

    <div class="event-item__body">
      <div class="event-item__body__description">
        <div class="event-item__body__date">{{ date }}</div>
        <div class="event-item__body__day">{{ day }}</div>
      </div>
      <a :href="eventLink" target="_blank">
        <button class="btn-blue">RSVP</button>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Secondary Event',

  props: {
    name: String,
    date: String,
    day: String,
    image: String,
    eventLink: String
  }
}
</script>

<style lang="scss">
@import '../assets/css/colors';

.event-item {
  width: calc(33.3333% - 40px);
  min-width: 300px;
  box-sizing: border-box;
  box-shadow: 0 2px 5px rgba(0,0,0,0.5);
  margin: 20px 20px;

  &__heading {
    position: relative;
    height:120px;
    overflow:hidden;
    background-color: $matryx-darker-grey;
    // margin-bottom: 10px;
    // box-sizing: border-box;

    &__img {
      position:absolute;
      width: 100%;
      // opacity: 0.5;
      // max-height: 110px;
      // height: auto;
    }

    &__text {

      height: 65px;
      background-color: $matryx-darker-grey;
      padding: 15px 20px;
      position: absolute;
      top: 30px;
      width: calc(100% - 40px);
      left: 20px;

      h4 {
        overflow: hidden;
        position: relative;
        line-height: 1.15em;
        max-height: 2.3em;
        text-align: left;
        margin-right: -1em;
        padding-right: 1em;
        color: $white;
      }
      h4:before {
        content: '...';
        background-color:$matryx-darker-grey;
        position: absolute;
        right: 22px;
        bottom: 0;
      }
      h4:after {
        content: '';
        background-color:$matryx-darker-grey;
        position: absolute;
        right: 22px;
        width: 1em;
        height: 1em;
        margin-top: 0.2em;
      }
    }

    &__name {
      color: $purple;
      font-size: 14px;
    }
  }

  &__body {
    width: 100%;
    margin: 0 auto;
    padding: 20px 40px;
    display: flex;
    flex-direction: column;
    align-items: center;

    &__description {
      color: $matryx-dark-grey;
      font-size: 18px;
      width: 100%;
      padding-bottom: 14px;
    }
  }

  button.btn-blue {
    font-size: 14px;
    padding: 5px 30px;
    margin-top: 30px;
    border-radius: 25px;
  }
}
</style>
