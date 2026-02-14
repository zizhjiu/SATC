<script>
import Title from './sections/Title.vue'
import Abstract from './sections/Abstract.vue'
import Overview from './sections/Overview.vue'
import Markdown from './sections/Markdown.vue'
import BibTeX from './sections/BibTeX.vue'
import ImageSlider from './sections/ImageSlider.vue'
import ImageSliderInner from './sections/ImageSliderInner.vue'
import ImageSelector from './sections/ImageSelector.vue'
import Echart from './sections/Echart.vue'
import Table from './sections/Table.vue'
import Collapse from './sections/Collapse.vue'
import SeletionForComparison from './sections/SeletionForComparison.vue'
import Latex from './sections/Latex.vue'


export default {
  components: {
    Title,
    Overview,
    Abstract,
    Markdown,
    BibTeX,
    ImageSlider,
    ImageSliderInner,
    ImageSelector,
    Echart,
    Collapse,
    Table,
    SeletionForComparison,
    Comment,
    Latex,
  }
}
</script>

<template>
  <Title/>
  <Overview/>
  <Abstract/>
  <Markdown/>
  <Latex/>
  <Table/>
  <Collapse/>
  <Echart/>

  <SeletionForComparison/>
  <ImageSliderInner/>
  <ImageSlider/>
  <ImageSelector/>
  <BibTeX/>
</template>