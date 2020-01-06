
<template>
<div>
    <h1>{{ text }}</h1>
    <div id="search">
         <form class="form1" action='#'>
            <input v-model='text' name='search' class="search" placeholder='検索...'>
            <input type="submit" value="検索" class="btn">
        </form>
    </div>
    <div id="shop">
        <div class="shop_namelist" v-for="(list, index) in shoplists" v-bind:key = index>
        <p>名前:{{list.shop_name}}</p>
        </div>
    </div>
</div>
</template>

<script>
export default({
  data: function () {
    return {
      text: '',
      shoplists: [
        {'shop_name': 'マルナカ'},
        {'shop_name': 'FUJI'},
        {'shop_name': 'LAMU'},
        {'shop_name': '柿安'},
        {'shop_name': 'サニつば'}
      ]
    }
  }
})
</script>
