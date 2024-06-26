<script setup lang="ts">
import Basic from './basic.vue';
import Plain from './plain.vue';
import Round from './round.vue';
import Text from './text.vue'
import Circle from './circle.vue'
import Icon from './icon.vue'
import Disabled from './disabled.vue'
import Size from './size.vue'
import Loading from './loading.vue'
import ClickEffect from './clickEffect.vue'

</script>

# Button

常用的操作按钮。

## 主要按钮

<Basic />

::: details 查看代码

<<< ./basic.vue

:::

## 次要按钮

<Plain/>

::: details 查看代码

<<< ./plain.vue

:::


## 文字按钮

<Text/>

::: details 查看代码

<<< ./text.vue

:::

## 圆角按钮

<Round/>

::: details 查看代码

<<< ./round.vue

:::


## 圆形按钮

<Circle/>

::: details 查看代码

<<< ./circle.vue

:::

## 图标按钮

直接将图标插入到文字的前面或者后面即可

<Icon/>

::: details 查看代码

<<< ./icon.vue

:::

## 不同大小

<Size />

::: details 查看代码

<<< ./size.vue

:::

## 不同点击效果

<ClickEffect />

::: details 查看代码

<<< ./clickEffect.vue

:::

## 禁用状态

<Disabled />

::: details 查看代码

<<< ./disabled.vue

:::

## 加载状态

<Loading />

::: details 查看代码

<<< ./loading.vue

:::

## API

### defineProps

<!--@include: ./defineProps.md-->

### defineEmits

<!--@include: ./defineEmits.md-->