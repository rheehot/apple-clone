<script>
    import { Collapse, Container, Nav, Navbar, NavbarBrand, NavbarToggler, NavItem, NavLink } from 'sveltestrap'
</script>

<nav>
    <div class="content">
        <a href="#" class="logo">
            <a class="logo " href="#">
                <img src="https://www.apple.com/ac/globalnav/3/en_US/images/globalnav/apple/image_large.svg" width="45" height="45" alt="">
            </a>
        </a>
        
        <a href="#">Mac</a>
        <a href="#">iPad</a>
        <a href="#">iPhone</a>
        <a href="#">Watch</a>
        <a href="#">TV</a>
        <a href="#">Music</a>
        <a href="#">Support</a>
        <a href="#" class="search"></a>
        <a href="#" class="bag"></a>
    </div>
</nav>

<style>
    nav {
        background: rgba(0,0,0,0.8);
        backdrop-filter: saturate(100%) blur(20px);
    }
    nav .content {
        max-width: 1024px;
        margin: 0 auto;
        padding: 0 20px;
        display: flex;
        justify-content: space-between;
    }
    nav .content a {
        position: relative;
        font-size: 14px;
        font-weight: 400;
        letter-spacing: -.01em;
        line-height: 3.14286;
        text-decoration: none;
        opacity: .8;
        color: #f5f5f7;
    }

    nav .content a[href]:hover {
        opacity: 1;
    }

    nav .search {
        background-position: 0 0;
        background-size: 18px 88px;
        background-repeat: no-repeat;
        background-image: url(https://www.apple.com/ac/globalnav/6/en_US/images/be15095f-5a20-57d0-ad14-cf4c638e223a/globalnav_search_image__fca9mfoh8a2q_large.svg);
        width: 18px;
        opacity: .8;
    }

    nav .search:hover {
        opacity: 1;
    }

    nav .bag {
        background-size: 17px 44px;
        background-repeat: no-repeat;
        background-image: url(https://www.apple.com/ac/globalnav/6/en_US/images/be15095f-5a20-57d0-ad14-cf4c638e223a/globalnav_bag_image__bmix8075eg4i_large.svg);
        background-position: center center;
        width: 17px;
        opacity: 0.7;
    }

    nav .bag:hover {
        opacity: 1;
    }
</style>