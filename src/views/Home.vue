<template>
  <main class="home">
    <div class="container">
      <div class="head flex wrap">
        <div class="box left">
          <div class="news">
            <img
              src="https://www.vpopwire.com/wp-content/uploads/2020/03/sao-anh-chua-ve-nha-amee-vpop.jpg"
              alt=""
            />
            <div class="content">
              <h1>Amee trở lại với màn comeback cự kỳ táo bạo</h1>
              <p class="author"><span>Xuân Sơn</span> - Th 8, 2021</p>
            </div>
          </div>
        </div>
        <div class="box right flex wrap">
          <div class="box" v-for="i in list" :key="i">
            <div class="news">
              <img :src="i" />
              <div class="content">
                <h1>Amee trở lại với màn comeback cự kỳ táo bạo</h1>
                <p class="author"><span>Xuân Sơn</span> - Th 8, 2021</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row center">
        <div class="col-8">
          <div class="category hot-news">
            <h1 class="border-gradient"><span>Tin hot</span></h1>
            <div class="row">
              <div class="col-6">
                <div class="right">
                  <img
                    src="https://www.vpopwire.com/wp-content/uploads/2020/03/sao-anh-chua-ve-nha-amee-vpop.jpg"
                    alt=""
                  />
                  <h2 class="title-news">
                    Amee trở lại với màn comeback cự kỳ táo bạo
                  </h2>
                  <p class="author"><span>Xuân Sơn</span> - Th 8, 2021</p>
                  <div class="detail">
                    Amee (tên thật là Trần Huyền My), sinh năm 2000 tại Hà Nội.
                    Cô hiện đang là nghệ sĩ trực thuộc St.319 Entertaiment. Đây
                    từng là công ty quản lý của các ca sĩ nổi tiếng như Erik,
                    Min.
                  </div>
                </div>
              </div>
              <div class="col-6">
                <div class="left">
                  <div class="news2" v-for="i in list" :key="i">
                    <img :src="i" />
                    <div>
                      <h3 class="title-news">Amee trở lại với màn comeback cự kỳ táo bạo</h3>
                      <p class="author"><span>Xuân Sơn</span> - Th 8, 2021</p>
                    </div>
                  </div>
                  <div class="news2" v-for="i in list" :key="i">
                    <img :src="i" />
                    <div>
                      <h3 class="title-news">Amee trở lại với màn comeback cự kỳ táo bạo</h3>
                      <p class="author"><span>Xuân Sơn</span> - Th 8, 2021</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="category">
            <h1 class="border-gradient border-pink">
              <span class="pink">Tin mới</span>
            </h1>
            <div class="flex wrap">
              <div class="box" v-for="i in list" :key="i">
                <div class="news">
                  <img :src="i" />
                  <div class="content">
                    <h1>Amee trở lại với màn comeback cự kỳ táo bạo</h1>
                    <p class="author"><span>Xuân Sơn</span> - Th 8, 2021</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="category hot-news">
            <h1 class="border-gradient"><span>Trending</span></h1>
            <div class="row">
              <div class="col-6">
                <div class="right">
                  <img
                    src="https://www.vpopwire.com/wp-content/uploads/2020/03/sao-anh-chua-ve-nha-amee-vpop.jpg"
                    alt=""
                  />
                  <h2 class="title-news">Amee trở lại với màn comeback cự kỳ táo bạo</h2>
                  <p class="author"><span>Xuân Sơn</span> - Th 8, 2021</p>
                  <div class="detail">
                    Amee (tên thật là Trần Huyền My), sinh năm 2000 tại Hà Nội.
                    Cô hiện đang là nghệ sĩ trực thuộc St.319 Entertaiment. Đây
                    từng là công ty quản lý của các ca sĩ nổi tiếng như Erik,
                    Min.
                  </div>
                </div>
              </div>
              <div class="col-6">
                <div class="left">
                  <div class="news2" v-for="i in list" :key="i">
                    <img :src="i" />
                    <div>
                      <h3 class="title-news">Amee trở lại với màn comeback cự kỳ táo bạo</h3>
                      <p class="author"><span>Xuân Sơn</span> - Th 8, 2021</p>
                    </div>
                  </div>
                  <div class="news2" v-for="i in list" :key="i">
                    <img :src="i" />
                    <div>
                      <h3 class="title-news">Amee trở lại với màn comeback cự kỳ táo bạo</h3>
                      <p class="author"><span>Xuân Sơn</span> - Th 8, 2021</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="category all-news">
            <h1 class="border-gradient border-pink">
              <span class="pink">Tất cả</span>
            </h1>
            <div class="row">
              <div class="col-12">
                <div class="news2" v-for="i in list" :key="i">
                  <img :src="i" />
                  <div>
                    <h3 class="title-news">
                      Amee trở lại với màn comeback cự kỳ táo bạo. Amee trở lại
                      với màn comeback cự kỳ táo bạo
                    </h3>
                    <p class="author"><span>Xuân Sơn</span> - Th 8, 2021</p>
                    <p class="detail">
                      Amee (tên thật là Trần Huyền My), sinh năm 2000 tại Hà
                      Nội. Cô hiện đang là nghệ sĩ trực thuộc St.319
                      Entertaiment.
                    </p>
                  </div>
                </div>
                <div class="news2" v-for="i in list" :key="i">
                  <img :src="i" />
                  <div>
                    <h3 class="title-news">
                      Amee trở lại với màn comeback cự kỳ táo bạo. Amee trở lại
                      với màn comeback cự kỳ táo bạo
                    </h3>
                    <p class="author"><span>Xuân Sơn</span> - Th 8, 2021</p>
                    <p class="detail">
                      Amee (tên thật là Trần Huyền My), sinh năm 2000 tại Hà
                      Nội. Cô hiện đang là nghệ sĩ trực thuộc St.319
                      Entertaiment.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-4">
          <div class="right-content">
            <div class="social">
              <div class="flex">
                <span>
                  <img src="../assets/icons/facebook.svg" alt="" />
                  1.989.369
                </span>
                <p>Like</p>
              </div>
              <div class="flex">
                <span>
                  <img src="../assets/icons/instagram.svg" alt="" />
                  189.369
                </span>
                <p>Follow</p>
              </div>
              <div class="flex">
                <span>
                  <img src="../assets/icons/twitter.svg" alt="" />
                  989.369
                </span>
                <p>Follow</p>
              </div>
            </div>
            <div class="category hot-news">
              <h1 class="border-gradient"><span>Trending</span></h1>
              <div class="row">
                <div class="col-12">
                  <div class="left">
                    <div class="news2" v-for="i in list" :key="i">
                      <img :src="i" />
                      <div>
                        <h3 class="title-news">Amee trở lại với màn comeback cự kỳ táo bạo</h3>
                        <p class="author"><span>Xuân Sơn</span> - Th 8, 2021</p>
                      </div>
                    </div>
                    <div class="news2" v-for="i in list" :key="i">
                      <img :src="i" />
                      <div>
                        <h3 class="title-news">Amee trở lại với màn comeback cự kỳ táo bạo</h3>
                        <p class="author"><span>Xuân Sơn</span> - Th 8, 2021</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "Home",
  data() {
    return {
      list: [
        "https://i.pinimg.com/236x/a5/87/2b/a5872b583d61a6f4b36fcab9f91dcb03.jpg",
        "https://i.pinimg.com/564x/d5/57/84/d55784b812e3a18fe525dca7299e7046.jpg",
        "https://i.pinimg.com/originals/2d/fb/d6/2dfbd60adc5b1d1daef182f8567eb300.jpg",
        "https://i.pinimg.com/originals/39/fa/5b/39fa5b9ec011a648737c5bd982a2f650.png",
      ],
    };
  },
};
</script>