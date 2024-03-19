<template>
    <v-sheet :elevation="5"
    height="500"
    width="400"
    class="pa-4 mx-auto mt-16 rounded-lg"
    >
        <div class="d-flex flex-column">
            <v-card-title class="align-self-center">
                FIT LOG
            </v-card-title>
            <v-text-field
                variant="underlined"
                placeholder="이메일을 입력하세요."
                color="indigo"
            ></v-text-field>
            <v-text-field
                variant="underlined"
                placeholder="비밀 번호를 입력하세요."
                type="password"
                color="indigo"
                class="mb-5"
            ></v-text-field>
            <v-btn color="indigo-accent-3">로그인</v-btn>
            <div class="d-flex justify-space-between">
                <v-btn 
                    color="grey-darken-3" 
                    variant="plain" 
                    size="small"
                    :ripple="false"
                >
                    회원가입
                </v-btn>
                <v-btn 
                    color="grey-darken-3" 
                    variant="plain" 
                    size="small"
                    :ripple="false"
                >
                    비밀번호 찾기
                </v-btn>
            </div>
            <!-- <button class="mt-10">
                <img src="/src/assets/kakao_login_large_wide.png" class="w-100 social-h" />
            </button>
            <button class="social-h">
                <img src="/src/assets/naver-600-90.png" class="w-100 social-h" />
            </button> -->
        </div>
  </v-sheet>
</template>
<script>
export default {
    
}
</script>
<style>
.social-h {
    height: 20%;
}
</style>