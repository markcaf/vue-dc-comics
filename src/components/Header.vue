<template>
    <header class="container">
        <nav class="d-flex justify-content-between align-items-center py-3">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="DC Universe Logo">
            </div>

            <ul class="list-unstyled">
                <li v-for="(link, index) in headerLinks" :key="index">
                    <a :class="{'active_link' : link.current}" :href="link.url">
                        {{ link.text }}
                    </a>
                </li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
  name: "Header",

  data:function(){
    return{
        headerLinks:[
            {
                text: 'Characters',
                url: '#',
                current: false,
            },

            {
                text: 'Comics',
                url: '#',
                current: true,
            },

            {
                text: 'Movies',
                url: '#',
                current: false,
            },
            
            {
                text: 'TV',
                url: '#',
                current: false,
            },
            
            {
                text: 'Games',
                url: '#',
                current: false,
            },
            
            {
                text: 'Collectibles',
                url: '#',
                current: false,
            },
            
            {
                text: 'Videos',
                url: '#',
                current: false,
            },
            
            {
                text: 'Fans',
                url: '#',
                current: false,
            },
            
            {
                text: 'News',
                url: '#',
                current: false,
            },
            
            {
                text: 'Shop',
                url: '#',
                current: false,
            },
            
        ],
    }
  }
};
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";

    ul{
        margin: 0;

        li{
            display: inline-block;
            padding: 1rem;
            text-transform: uppercase;
            font-weight: bold;
            font-size: 14px;
            color: #534f49;
            font-stretch: extra-condensed;

            a{
                text-decoration: none;
                color: #534f49;
                cursor: pointer;

                &.active_link{
                color: $brandColor;
                }

                &:hover{
                color: $brandColor;
                }
            }
        }
    }
</style>