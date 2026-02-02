/* 全体のリセット（最低限） */
body {
  background: #f7f7f7;
  margin: 0;
  padding: 20px;
  font-family: "Hiragino Mincho ProN", "游明朝", serif;
}

/* 日記本文エリア */
.diary {
  max-width: 600px;
  margin: 0 auto;
  padding: 20px 24px;
  background:
    repeating-linear-gradient(
      to bottom,
      #ffffff,
      #ffffff 28px,
      #cfcfcf 29px
    );
  border: 1px solid #bbb;
  line-height: 29px;
}

/* タイトル */
.diary h1 {
  font-size: 1.2em;
  text-align: center;
  margin: 0 0 29px 0;
}

/* 本文 */
.diary p {
  margin: 0;
