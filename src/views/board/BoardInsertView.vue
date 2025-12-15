<template>
    <div class="container">
        <div class="row">
            <h3 class="text-center">글쓰기</h3>
                <table class="table">
                    <tbody>
                        <tr>
                            <th width=15% class="text-center">이름</th>
                            <td width=85% class="text-left">
                                <input type=text name=name size=20 class="input-sm" required>
                            </td>
                        </tr>
                        <tr>
                            <th width=15% class="text-center">제목</th>
                            <td width=85% class="text-left">
                                <input type=text name=subject size=60 class="input-sm" required>
                            </td>
                        </tr>
                        <tr>
                            <th width=15% class="text-center">내용</th>
                            <td width=85% class="text-left">
                                <textarea rows="10" cols="60" name=content required></textarea>
                            </td>
                        </tr>
                        <tr>
                            <th width=15% class="text-center">비밀번호</th>
                            <td width=85% class="text-left">
                                <input type=password name=pwd size=10 class="input-sm" required>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2" class="text-center">
                                <button type=button class="btn-sm btn-primary">글쓰기</button>
                                <button type=button class="btn-sm btn-primary"
                                    onclick="javascript:history.back()">취소</button>
                            </td>
                        </tr>
                    </tbody>
                </table>
        </div>
    </div>
</template>
<script>

</script>
<style scoped>
    .row {
            margin: 0px auto;
            width: 800px
        }
</style>