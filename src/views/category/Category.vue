<template>
  <div class="wrapper">
    <ul class="content">
      <li>分类列表，测试better-scroll1</li>
      <li>分类列表，测试better-scroll2</li>
      <li>分类列表，测试better-scroll3</li>
      <li>分类列表，测试better-scroll4</li>
      <li>分类列表，测试better-scroll5</li>
      <li>分类列表，测试better-scroll6</li>
      <li>分类列表，测试better-scroll7</li>
      <li>分类列表，测试better-scroll8</li>
      <li>分类列表，测试better-scroll9</li>
      <li>分类列表，测试better-scroll10</li>
      <li>分类列表，测试better-scroll11</li>
      <li>分类列表，测试better-scroll12</li>
      <li>分类列表，测试better-scroll13</li>
      <li>分类列表，测试better-scroll14</li>
      <li>分类列表，测试better-scroll15</li>
      <li>分类列表，测试better-scroll16</li>
      <li>分类列表，测试better-scroll17</li>
      <li>分类列表，测试better-scroll18</li>
      <li>分类列表，测试better-scroll19</li>
      <li>分类列表，测试better-scroll20</li>
      <li>分类列表，测试better-scroll21</li>
      <li>分类列表，测试better-scroll22</li>
      <li>分类列表，测试better-scroll23</li>
      <li>分类列表，测试better-scroll24</li>
      <li>分类列表，测试better-scroll25</li>
      <li>分类列表，测试better-scroll26</li>
      <li>分类列表，测试better-scroll27</li>
      <li>分类列表，测试better-scroll28</li>
      <li>分类列表，测试better-scroll29</li>
      <li>分类列表，测试better-scroll30</li>
      <li>分类列表，测试better-scroll31</li>
      <li>分类列表，测试better-scroll32</li>
      <li>分类列表，测试better-scroll33</li>
      <li>分类列表，测试better-scroll34</li>
      <li>分类列表，测试better-scroll35</li>
      <li>分类列表，测试better-scroll36</li>
      <li>分类列表，测试better-scroll37</li>
      <li>分类列表，测试better-scroll38</li>
      <li>分类列表，测试better-scroll39</li>
      <li>分类列表，测试better-scroll40</li>
      <li>分类列表，测试better-scroll41</li>
      <li>分类列表，测试better-scroll42</li>
      <li>分类列表，测试better-scroll43</li>
      <li>分类列表，测试better-scroll44</li>
      <li>分类列表，测试better-scroll45</li>
      <li>分类列表，测试better-scroll46</li>
      <li>分类列表，测试better-scroll47</li>
      <li>分类列表，测试better-scroll48</li>
      <li>分类列表，测试better-scroll49</li>
      <li>分类列表，测试better-scroll50</li>
      <li>分类列表，测试better-scroll51</li>
      <li>分类列表，测试better-scroll52</li>
      <li>分类列表，测试better-scroll53</li>
      <li>分类列表，测试better-scroll54</li>
      <li>分类列表，测试better-scroll55</li>
      <li>分类列表，测试better-scroll56</li>
      <li>分类列表，测试better-scroll57</li>
      <li>分类列表，测试better-scroll58</li>
      <li>分类列表，测试better-scroll59</li>
      <li>分类列表，测试better-scroll60</li>
      <li>分类列表，测试better-scroll61</li>
      <li>分类列表，测试better-scroll62</li>
      <li>分类列表，测试better-scroll63</li>
      <li>分类列表，测试better-scroll64</li>
      <li>分类列表，测试better-scroll65</li>
      <li>分类列表，测试better-scroll66</li>
      <li>分类列表，测试better-scroll67</li>
      <li>分类列表，测试better-scroll68</li>
      <li>分类列表，测试better-scroll69</li>
      <li>分类列表，测试better-scroll70</li>
      <li>分类列表，测试better-scroll71</li>
      <li>分类列表，测试better-scroll72</li>
      <li>分类列表，测试better-scroll73</li>
      <li>分类列表，测试better-scroll74</li>
      <li>分类列表，测试better-scroll75</li>
      <li>分类列表，测试better-scroll76</li>
      <li>分类列表，测试better-scroll77</li>
      <li>分类列表，测试better-scroll78</li>
      <li>分类列表，测试better-scroll79</li>
      <li>分类列表，测试better-scroll80</li>
      <li>分类列表，测试better-scroll81</li>
      <li>分类列表，测试better-scroll82</li>
      <li>分类列表，测试better-scroll83</li>
      <li>分类列表，测试better-scroll84</li>
      <li>分类列表，测试better-scroll85</li>
      <li>分类列表，测试better-scroll86</li>
      <li>分类列表，测试better-scroll87</li>
      <li>分类列表，测试better-scroll88</li>
      <li>分类列表，测试better-scroll89</li>
      <li>分类列表，测试better-scroll90</li>
      <li>分类列表，测试better-scroll91</li>
      <li>分类列表，测试better-scroll92</li>
      <li>分类列表，测试better-scroll93</li>
      <li>分类列表，测试better-scroll94</li>
      <li>分类列表，测试better-scroll95</li>
      <li>分类列表，测试better-scroll96</li>
      <li>分类列表，测试better-scroll97</li>
      <li>分类列表，测试better-scroll98</li>
      <li>分类列表，测试better-scroll99</li>
      <li>分类列表，测试better-scroll100</li>
    </ul>
  </div>
</template>

<script>
import BScroll from "better-scroll";
export default {
  name: "Category",
  data() {
    return {
      scroll: null
    }
  },

  mounted() {
    // console.log(this.$refs.aaaa);
    this.scroll = new BScroll(document.querySelector(".wrapper"), {
      probeType:3,
      pullUpLoad:true,

    });
    this.scroll.on('scroll',(position) =>{
      console.log(position);
    }),
    this.scroll.on('pullingUp',()=>{
      console.log('上拉加载更多');
    })
  },
};
</script>

<style scoped>
.wrapper {
  height: 150px;
  background-color: pink;
  overflow: hidden;
}
</style>
