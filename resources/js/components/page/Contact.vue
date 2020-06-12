<template> <!-- Vue.jsでのHTML部分を記述します。必ずtemplateタグから始まります -->
    <div>
        <the-header></the-header>

        <!-- メイン -->
        <main class="contact mt-4">
            <div class="container">
                <!-- タイトル -->
                <h1 class="mb-4">お問い合わせ</h1>
                <!-- コンテンツ -->
                <div class="row justify-content-center">
                    <div class="col-md-9 py-4">
                        <form action="" method="post">
                            <div class="form-group row mb-3">
                                <label for="inputName" class="col-md-3 col-form-label text-left text-md-right">お名前</label>
                                <div class="col-md-9">
                                    <input type="text" class="form-control" id="inputName">
                                </div>
                            </div>
                            <div class="form-group row mb-3">
                                <label for="inputMailAddress" class="col-md-3 col-form-label text-left text-md-right">メールアドレス</label>
                                <div class="col-md-9">
                                    <input type="email" class="form-control" id="inputMailAddress">
                                </div>
                            </div>
                            <div class="form-group row mb-3">
                                <label for="inputContent" class="col-md-3 col-form-label text-left text-md-right">お問い合わせ内容</label>
                                <div class="col-md-9">
                                    <textarea class="form-control" id="inputContent" cols="30" rows="7"></textarea>
                                </div>
                            </div>
                            <button type="submit" class="btn btn-success btn-lg my-1">送信</button>
                        </form>

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