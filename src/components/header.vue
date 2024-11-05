<script setup>
    
</script>


<template>
    <header>
        <div class="container">
            <nav>
                <div class="nav-list">
                    <h2>LOGO</h2>
                    <ul>
                        <li><a href="#">Service</a></li>
                        <li><a href="#">Agency</a></li>
                        <li><a href="#">Case study</a></li>
                        <li><a href="#">Resources</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>
                </div>
                <div class="nav-actions">
                        <button>Get Started</button>
                        <button><i class='bx bx-bell'></i></button>
                </div>
            </nav>
        </div>
    </header>
</template>



<style lang="scss" scoped>
    header{
        padding: 40px 0;
    }

    nav{
        display: flex;
        align-items: center;
        justify-content: space-between;

        .nav-list{
            display: flex;
            align-items: center;
            gap: 65px;

            h2{
                font-size: 28px;
            }

            ul{
                display: flex;
                align-items: center;
                gap: 15px;

                li{
                    a{
                        color: black;
                        font-size: 16px;
                        text-transform: uppercase;
                        font-weight: 500;
                    }
                }
            }
        }

        .nav-actions{
            display: flex;
            align-items: center;
            gap: 15px;

            button:first-child{
                padding: 13px 35px;
                border-radius: 50px;
                font-weight: 700;
                font-size: 16px;
                cursor: pointer;
            }

            button:last-child{
                padding: 5px;
                border-radius: 50%;
                font-size: 24px;
                color: white;
                background: black;
                cursor: pointer;
            }
        }
    }
</style>