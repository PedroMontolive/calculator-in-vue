<script setup>
import ButtonOperator from '../Components/ButtonOperator/ButtonOperator.vue';

</script>

<script>

export default {
  data() {
    return {

    }
  },
  methods:{

  }
}
</script>

<template>
  <div class="calculator">
      <div class="result"><p></p></div>

      <div class="line">
        <ButtonOperator bggcolor="gray" text="AC" :value="'AC'"/>
        <ButtonOperator bggcolor="gray" text="+/-" :value="'+/-'"/>
        <ButtonOperator bggcolor="gray" text="%" :value="'%'"/>
        <ButtonOperator bggcolor="orange" text="/" :value="'/'"/>
      </div>

      <div class="line">
        <ButtonOperator bggcolor="dark-gray" text="7" :value="'7'"/>
        <ButtonOperator bggcolor="dark-gray" text="8" :value="'8'"/>
        <ButtonOperator bggcolor="dark-gray" text="9" :value="'9'"/>
        <ButtonOperator bggcolor="orange" text="*" :value="'*'"/>
      </div>

      <div class="line">
        <ButtonOperator bggcolor="dark-gray" text="4" :value="'4'"/>
        <ButtonOperator bggcolor="dark-gray" text="5" :value="'5'"/>
        <ButtonOperator bggcolor="dark-gray" text="6" :value="'6'"/>
        <ButtonOperator bggcolor="orange" text="-" :value="'-'"/>
      </div>

      <div class="line">
        <ButtonOperator bggcolor="dark-gray" text="1" :value="'1'"/>
        <ButtonOperator bggcolor="dark-gray" text="2" :value="'2'"/>
        <ButtonOperator bggcolor="dark-gray" text="3" :value="'3'"/>
        <ButtonOperator bggcolor="orange" text="+" :value="'+'"/>
      </div>
 
      <div class="line">
        <ButtonOperator bggcolor="dark-gray-zero" text="0" :value="'0'"/>
        <ButtonOperator bggcolor="dark-gray" text="." :value="'.'"/>
        <ButtonOperator bggcolor="orange" text="=" :value="'='"/>
      </div>

  </div>
</template>

<style src="../assets/scss/style.scss" lang="scss" scoped/>