<template>
    <div>
        <h3>{{operation}}</h3>
        <textarea rows="4" readonly>
            let x=2
            let y=3
            x/=y
            console.log(x,y) //注意js里没有整除这个概念
        </textarea>
        <br>
        <button @click="x/=y">除法赋值结果</button>
        <br>
        <textarea rows="1" readonly>
            <!-- {{x}} {{y}} -->
        </textarea>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="">
    
</style>