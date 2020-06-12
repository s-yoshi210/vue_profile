<template> <!-- Vue.jsでのHTML部分を記述します。必ずtemplateタグから始まります -->
    <div>
        <the-header></the-header>

        <!-- メイン -->
        <main class="development mt-4">
            <div class="container text-center">
                <!-- タイトル -->
                <h1 class="mb-4">個人開発成果物</h1>
                <!-- コンテンツ -->
                <div class="row justify-content-center">
                    <div class="col-md-10 py-4">
                        <div class="card text-left">
                            <div class="card-header font-weight-bold">
                                <i class="far fa-file-code mx-3"></i><span>自己紹介サイト</span>
                            </div>
                            <div class="card-body">
                                <table class="table">
                                    <tr>
                                        <th class="text-center">開発理由</th>
                                        <td>
                                            aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
                                        </td>
                                    </tr>
                                    <tr>
                                        <th class="text-center">内容</th>
                                        <td>
                                            aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
                                        </td>
                                    </tr>
                                    <tr>
                                        <th class="text-center">開発環境</th>
                                        <td>bbbbbbbbbbbbbbbbbbbbbbbbbbbbbb</td>
                                    </tr>
                                    <tr>
                                        <th class="text-center">GitHub</th>
                                        <td><a href="https://github.com/s-yoshi210/profile">こちら</a></td>
                                    </tr>
                                    <tr>
                                        <th class="text-center">デモサイト</th>
                                        <td>
                                            <a href="#">https://xxxxxxxxx</a>
                                            <p>簡単ログイン機能を使用してください。</p>
                                        </td>
                                    </tr>
                                    <tr>
                                        <th class="text-center">コメント</th>
                                        <td>
                                            ccccccccccccccccccccccccccccccc
                                        </td>
                                    </tr>
                                </table>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-10 py-4">
                        <div class="card text-left">
                            <div class="card-header font-weight-bold">
                                <i class="far fa-file-code mx-3"></i><span>自己紹介サイト</span>
                            </div>
                            <div class="card-body">
                                <table class="table">
                                    <tr>
                                        <th class="text-center">開発理由</th>
                                        <td>
                                            aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
                                        </td>
                                    </tr>
                                    <tr>
                                        <th class="text-center">内容</th>
                                        <td>
                                            aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
                                        </td>
                                    </tr>
                                    <tr>
                                        <th class="text-center">開発環境</th>
                                        <td>bbbbbbbbbbbbbbbbbbbbbbbbbbbbbb</td>
                                    </tr>
                                    <tr>
                                        <th class="text-center">GitHub</th>
                                        <td><a href="https://github.com/s-yoshi210/profile">こちら</a></td>
                                    </tr>
                                    <tr>
                                        <th class="text-center">デモサイト</th>
                                        <td>
                                            <a href="#">https://xxxxxxxxx</a>
                                            <p>簡単ログイン機能を使用してください。</p>
                                        </td>
                                    </tr>
                                    <tr>
                                        <th class="text-center">コメント</th>
                                        <td>
                                            ccccccccccccccccccccccccccccccc
                                        </td>
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