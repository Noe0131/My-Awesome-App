<script setup>

</script>

<template>
<!-- ナビゲーションバー -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">レシピ集</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="ナビゲーションメニューを切り替える">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">ホーム</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">レシピ一覧</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">お問い合わせ</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<!-- タイトルと紹介文 -->
<div class="container mt-4 bg-light p-4 rounded">
  <h1 class="display-1 text-center text-primary">美味しさNo.１！KFC風フライドチキン</h1>
  <p class="h2 text-center text-secondary">KFC人気レシピ1位！数あるKFCレシピ─どれも何か一味足りない気が。<br>試行錯誤の末の主人も絶賛☆再現率の高いレシピです☆</p>
</div>

<!-- 材料、作り方、コツ・ポイント -->
<div class="container mt-4">
  <div class="row gx-5">
    <!-- 材料 -->
    <div class="col-12 col-md-4 border p-4 bg-light">
      <h2 class="text-center text-primary">材料</h2>
      <ul class="list-unstyled">
        <li>鶏肉(お好きな部位) ２〜３枚位</li>
        <li>☆牛乳 1/2カップ</li>
        <li>☆卵 <small>１個</small></li>
        <li>☆にんにくチューブ ２センチ位</li>
        <li>★薄力粉 １カップ</li>
        <li>★オールスパイス 小さじ１弱</li>
        <li>★顆粒コンソメ 大さじ1/2</li>
        <li>★塩 大さじ1/2</li>
        <li>あれば★パプリカパウダー 小さじ１</li>
      </ul>
    </div>
    
    <!-- 作り方 -->
    <div class="col-12 col-md-4 border p-4 bg-light">
      <h2 class="text-center text-primary">作り方</h2>
      <ol>
        <li>☆をボウルに混ぜ合わせておく。</li>
        <li>別のボウルに★を全て混ぜ合わせておく。</li>
        <li>肉の厚みがある部分を切り開き、厚みを一定にする。鶏肉１枚を２～３等分の大きめに切る。</li>
        <li>１のボウルに鶏肉を浸す。(時間があれば20分以上浸す。)</li>
        <li>２のボウルに鶏肉を入れて粉類をまんべんなくまぶし、別の容器に並べていく。粉が余るようでしたら、二度付けをお勧めします！</li>
        <li>卵液→粉→卵液→粉と二度付けする事で、カリっと感がアップ＋味もしっかり付きます！写真の我が家のは二度付けしています。</li>
        <li>油を160度に温める。(温めるのはこのタイミングで大丈夫です。待ってる間に衣が鶏肉になじみます。)</li>
        <li><u>160度で５分</u>以上、様子を見ながら、火が通ったら、一度上げて、今度は180～200度でカリっと仕上げ、完成です☆</li>
        <li>鶏肉の1枚はサイズにばらつきがある為、2～3枚という記載に変更しました。</li>
      </ol>
    </div>
    
    <!-- コツ・ポイント -->
    <div class="col-12 col-md-4 border p-4 bg-light">
      <h3 class="text-center text-primary">コツ・ポイント</h3>
      <p class="text-secondary">揚げる際鍋底での焦げ防止に衣が軽く揚がるまで菜箸等で時々浮かせて下さい。好みで粉類に粗びき黒胡椒小さじ1/2を足しても◎<br>
      にんにくチューブ２センチはガーリックパウダー小さじ１に変えて粉類と混ぜても美味しいです。<br>
      パプリカパウダーは無くても可</p>
    </div>
  </div>
</div>

<!-- レシピの生い立ち -->
<div class="container mt-4 bg-secondary p-4 rounded">
  <h3 class="text-center text-primary">このレシピの生い立ち</h3>
  <p class="text-light">今まで作った<mark>KFCレシピ</mark>は、卵液や粉もかなり余るし、何よりも何かひと味足りない……と思って、やっとKFC味にたどり着きました！</p>
  <blockquote class="blockquote text-center mt-4 border-left-primary pl-4">
    <p class="mb-0 text-light">どの家庭にもあるような材料で☆<br>
    牛乳と卵液、粉類も必要量のみになっているので無駄が無く経済的です☆</p>
  </blockquote>
</div>

</template>

<style>

</style>