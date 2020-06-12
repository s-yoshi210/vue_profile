<template> <!-- Vue.jsでのHTML部分を記述します。必ずtemplateタグから始まります -->
  <div>
    <the-header></the-header>

      <!-- メイン -->
      <main class="profile mt-4 mt-md-5">
          <div class="container text-center">
              <!-- タイトル -->
              <h1>プロフィール</h1>
              <!-- コンテンツ -->
              <div class="row justify-content-center mt-md-5">
                  <div class="col-md-5">
                      <img src="/images/猫.png" class="rounded-circle" alt="">
                  </div>
                  <div class="col-md-5 mt-3 text-left">
                      <div class="row">
                          <div class="col-md-12 minh-300">
                              <p>
                                  Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                              </p>
                          </div>
                          <div class="col-md-12">
                              <table class="table text-center">
                                  <tr>
                                      <th>GitHub</th>
                                      <td><a href="https://github.com/s-yoshi210">s-yoshi210</a></td>
                                  </tr>
                                  <tr>
                                      <th>Twitter</th>
                                      <td><a href="https://twitter.com/SYoshi210">Yoshi</a></td>
                                  </tr>
                                  <tr>
                                      <th>Qiita</th>
                                      <td><a href="https://qiita.com/s-yoshi210">s-yoshi210</a></td>
                                  </tr>
                              </table>
                          </div>
                      </div>
                  </div>
              </div>
          </div>
      </main>

      <the-footer></the-footer>

  </div>
</template>

<script>
    import TheHeader from "../layout/TheHeader";
    import TheFooter from "../layout/TheFooter";

    export default {
        components: {
            TheHeader,
            TheFooter,
        }
    };
</script>