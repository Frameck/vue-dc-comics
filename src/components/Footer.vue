<template>
  <div class="footer-container">
        <footer class="footer">
            <!-- links -->
            <div class="list-container">
                <div class="list-container-left">
                    <ul>
                        <h3>DC COMICS</h3>
                        <li v-for="item,i in footerItems.dcComics" :key="i">
                            <a :href="item.href + item.text">{{ item.text }}</a>
                        </li>
                    </ul>

                    <ul>
                        <h3>SHOP</h3>
                        <li v-for="item,i in footerItems.shop" :key="i">
                            <a :href="item.href + item.text">{{ item.text }}</a>
                        </li>
                    </ul>
                </div>
                <div class="list-container-middle">
                    <ul>
                        <h3>DC</h3>
                        <li v-for="item,i in footerItems.dc" :key="i">
                            <a :href="item.href + item.text">{{ item.text }}</a>
                        </li>
                    </ul>
                </div>
                <div class="list-container-right">
                    <ul>
                        <h3>SITES</h3>
                        <li v-for="item,i in footerItems.sites" :key="i">
                            <a :href="item.href + item.text">{{ item.text }}</a>
                        </li>
                    </ul>
                </div>
            </div>
        </footer>
  </div>
</template>

<script>
export default {
    name: 'Footer',
    data() {
        return {
            footerItems: {
                dcComics: [
                    {
                        text: 'Characters',
                        href: '#'
                    },
                    {
                        text: 'Comics',
                        href: '#'
                    },
                    {
                        text: 'Movies',
                        href: '#'
                    },
                    {
                        text: 'TV',
                        href: '#'
                    },
                    {
                        text: 'Games',
                        href: '#'
                    },
                    {
                        text: 'Videos',
                        href: '#'
                    },
                    {
                        text: 'News',
                        href: '#'
                    }
                ],
                shop: [
                    {
                        text: 'Shop DC',
                        href: '#'
                    },
                    {
                        text: 'Shop DC Collectibles',
                        href: '#'
                    }
                ],
                dc: [
                    {
                        text: 'Terms Of Use',
                        href: '#'
                    },
                    {
                        text: 'Privacy policy (New)',
                        href: '#'
                    },
                    {
                        text: 'Ad Choices',
                        href: '#'
                    },
                    {
                        text: 'Advertising',
                        href: '#'
                    },
                    {
                        text: 'Jobs',
                        href: '#'
                    },
                    {
                        text: 'Subscriptions',
                        href: '#'
                    },
                    {
                        text: 'Talent Workshops',
                        href: '#'
                    },
                    {
                        text: 'CPSC Certificates',
                        href: '#'
                    },
                    {
                        text: 'Ratings',
                        href: '#'
                    },
                    {
                        text: 'Shop Help',
                        href: '#'
                    },
                    {
                        text: 'Contact Us',
                        href: '#'
                    }
                ],
                sites: [
                    {
                        text: 'DC',
                        href: '#'
                    },
                    {
                        text: 'MAD Magazine',
                        href: '#'
                    },
                    {
                        text: 'DC Kids',
                        href: '#'
                    },
                    {
                        text: 'DC Universe',
                        href: '#'
                    },
                    {
                        text: 'DC Power Visa',
                        href: '#'
                    }
                ]
            }
        }
    }
}
</script>

<style>

</style>