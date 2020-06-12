<template> <!-- Vue.jsでのHTML部分を記述します。必ずtemplateタグから始まります -->
    <div>
        <the-header></the-header>

        <!-- メイン -->
        <main class="actual_results mt-4">
            <div class="container text-center">
                <!-- タイトル -->
                <h1 class="mb-4">過去実績</h1>
                <!-- コンテンツ -->
                <div class="row justify-content-center">
                    <div class="col-md-10 py-3">
                        <div class="card text-left">
                            <div class="card-header font-weight-bold">
                                <i class="fas fa-tasks mx-3"></i><span>製薬会社におけるMR支援システム</span>
                            </div>
                            <div class="card-body">
                                <table class="table">
                                    <tr>
                                        <th class="text-center">案件内容</th>
                                        <td>
                                            aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
                                        </td>
                                    </tr>
                                    <tr>
                                        <th  class="text-center">担当業務</th>
                                        <td>bbbbbbbbbbbbbbbbbbbbbbbbbbbbbb</td>
                                    </tr>
                                    <tr>
                                        <th  class="text-center">開発環境</th>
                                        <td>
                                            ccccccccccccccccccccccccccccccc
                                        </td>
                                    </tr>
                                </table>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-10 py-3">
                        <div class="card text-left">
                            <div class="card-header font-weight-bold">
                                <i class="fas fa-tasks mx-3"></i><span>製薬会社におけるMR支援システム</span>
                            </div>
                            <div class="card-body">
                                <table class="table">
                                    <tr>
                                        <th class="text-center">案件内容</th>
                                        <td>
                                            aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
                                        </td>
                                    </tr>
                                    <tr>
                                        <th  class="text-center">担当業務</th>
                                        <td>bbbbbbbbbbbbbbbbbbbbbbbbbbbbbb</td>
                                    </tr>
                                    <tr>
                                        <th  class="text-center">開発環境</th>
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