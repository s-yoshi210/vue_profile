<template> <!-- Vue.jsでのHTML部分を記述します。必ずtemplateタグから始まります -->
    <div>
        <the-header></the-header>

        <!-- メイン -->
        <main class="skill my-4">
            <div class="container text-center">
                <!-- タイトル -->
                <h1 class="mb-4">スキルセット</h1>
                <!-- コンテンツ -->
                <div class="row justify-content-center">
                    <div class="col-md-6 py-3">
                        <div class="card">
                            <div class="card-header bg-primary text-white font-weight-bold">
                                <i class="fas fa-desktop mr-3"></i><span>フロントエンド</span>
                            </div>
                            <div class="card-body">
                                <p>案件で使用していました。</p>
                                <table class="table table-borderless">
                                    <thead>
                                    <tr>
                                        <th scope="col">技術</th>
                                        <th scope="col">経験年数</th>
                                    </tr>
                                    </thead>
                                    <tbody>
                                    <tr>
                                        <td>JavaScript</td>
                                        <td>5年</td>
                                    </tr>
                                    <tr>
                                        <td>jQuery</td>
                                        <td>5年</td>
                                    </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 py-3">
                        <div class="card">
                            <div class="card-header bg-success text-white font-weight-bold">
                                <i class="fas fa-desktop mr-3"></i><span>バックエンド</span>
                            </div>
                            <div class="card-body">
                                <p>案件で使用していました。</p>
                                <table class="table table-borderless">
                                    <thead>
                                    <tr>
                                        <th scope="col">技術</th>
                                        <th scope="col">経験年数</th>
                                    </tr>
                                    </thead>
                                    <tbody>
                                    <tr>
                                        <td>JavaScript</td>
                                        <td>5年</td>
                                    </tr>
                                    <tr>
                                        <td>jQuery</td>
                                        <td>5年</td>
                                    </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 py-3">
                        <div class="card">
                            <div class="card-header bg-secondary text-white font-weight-bold">
                                <i class="fas fa-desktop mr-3"></i><span>DB</span>
                            </div>
                            <div class="card-body">
                                <p>案件で使用していました。</p>
                                <table class="table table-borderless">
                                    <thead>
                                    <tr>
                                        <th scope="col">技術</th>
                                        <th scope="col">経験年数</th>
                                    </tr>
                                    </thead>
                                    <tbody>
                                    <tr>
                                        <td>JavaScript</td>
                                        <td>5年</td>
                                    </tr>
                                    <tr>
                                        <td>jQuery</td>
                                        <td>5年</td>
                                    </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 py-3">
                        <div class="card">
                            <div class="card-header bg-warning text-white font-weight-bold">
                                <i class="fas fa-desktop mr-3"></i><span>デザイン</span>
                            </div>
                            <div class="card-body">
                                <p>案件で使用していました。</p>
                                <table class="table table-borderless">
                                    <thead>
                                    <tr>
                                        <th scope="col">技術</th>
                                        <th scope="col">経験年数</th>
                                    </tr>
                                    </thead>
                                    <tbody>
                                    <tr>
                                        <td>JavaScript</td>
                                        <td>5年</td>
                                    </tr>
                                    <tr>
                                        <td>jQuery</td>
                                        <td>5年</td>
                                    </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 py-3">
                        <div class="card">
                            <div class="card-header bg-info text-white font-weight-bold">
                                <i class="fas fa-desktop mr-3"></i><span>インフラ・サーバー</span>
                            </div>
                            <div class="card-body">
                                <p>案件で使用していました。</p>
                                <table class="table table-borderless">
                                    <thead>
                                    <tr>
                                        <th scope="col">技術</th>
                                        <th scope="col">経験年数</th>
                                    </tr>
                                    </thead>
                                    <tbody>
                                    <tr>
                                        <td>JavaScript</td>
                                        <td>5年</td>
                                    </tr>
                                    <tr>
                                        <td>jQuery</td>
                                        <td>5年</td>
                                    </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 py-3">
                        <div class="card">
                            <div class="card-header bg-danger text-white font-weight-bold">
                                <i class="fas fa-desktop mr-3"></i><span>その他</span>
                            </div>
                            <div class="card-body">
                                <p>案件で使用していました。</p>
                                <table class="table table-borderless">
                                    <thead>
                                    <tr>
                                        <th scope="col">技術</th>
                                        <th scope="col">経験年数</th>
                                    </tr>
                                    </thead>
                                    <tbody>
                                    <tr>
                                        <td>JavaScript</td>
                                        <td>5年</td>
                                    </tr>
                                    <tr>
                                        <td>jQuery</td>
                                        <td>5年</td>
                                    </tr>
                                    </tbody>
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