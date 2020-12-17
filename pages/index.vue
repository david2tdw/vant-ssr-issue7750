<template>
  <div>
    <Swipe class="mobile-home-swipe" :autoplay="3000" indicator-color="#32C5FF" :loop="true">
      <SwipeItem>
        <div class="solution-item">
          <div>
            智能制造解决方案
          </div>
          <div>智能制造解决方案智能制造解决方案智能制造解决方案智能制造解决方案智能制造解决方案智能制造解决方案智能制造解决方案智能制造解决方案智能制造解决方案智能制造解决方案。 </div>
        </div>
      </SwipeItem>
      <SwipeItem>
        <div class="solution-item">
          <div>
            大数据服务与应用
          </div>
          <div>大数据服务与应用大数据服务与应用大数据服务与应用大数据服务与应用大数据服务与应用大数据服务与应用大数据服务与应用大数据服务与应用大数据服务与应用大数据服务与应用。</div>
        </div>
      </SwipeItem>
      <SwipeItem>
        <div class="solution-item">
          <div>
            工业互联网解决方案
          </div>
          <div>工业互联网解决方案工业互联网解决方案工业互联网解决方案工业互联网解决方案工业互联网解决方案工业互联网解决方案工业互联网解决方案工业互联网解决方案工业互联网解决方案。 </div>
        </div>
      </SwipeItem>
    </Swipe>
  </div>
</template>

<script>
import { Swipe, SwipeItem } from 'vant'
export default {
  name: 'Xxx',
  layout: 'mobile-layout',
  components: {
    Swipe,
    SwipeItem
  },
  data () {
    return {}
  },
  methods: {
  }
}
</script>

<style lang="stylus">
</style>
