<template>
  <div>
    <header>
      <div class="inner">
        <a href="#profile"
          ><h1><span>M</span><span>Portfolio</span></h1></a
        >
        <ul>
          <li>
            <a href="#profile">PROFILE</a>
          </li>
          <li><a href="#skill">SKILL</a></li>
          <li><a href="#works">WORKS</a></li>
          <li><a href="#contact">CONTACT</a></li>
        </ul>
      </div>
    </header>
    <div class="profile" id="profile">
      <div class="inner">
        <ul class="profile__name">
          <li><img src="../assets/img/me.png" alt="" /></li>
          <li>
            <p>Front-End Engineer</p>
            <p>SASAKI MICHINARI</p>
            <p>
              <a href="https://github.com/michinari-sasaki"
                >GitHub: @michinari-sasaki</a
              >
            </p>
          </li>
        </ul>
        <div class="profile__text">
          <p>
            はじめまして。佐々木道成と申します。<br />
            東京都在住のフロントエンドエンジニアです。<br />
            言語は特にPHPとJSが好きです。<br />
            社内ツールの制作やマークアップの他にもWEBデザインや<br />
            動画制作、印刷などに携わってきました。<br />
          </p>
          <dl>
            <dt>趣味</dt>
            <dd>
              ギター、絵を描くこと、動画制作、ボカロ<br />フロントの新技術に悶えながら勉強すること
            </dd>
          </dl>
        </div>
      </div>
    </div>
    <section class="skill" id="skill">
      <div class="inner">
        <h2 class="heading">SKILL</h2>
        <dl>
          <dt>言語</dt>
          <dd>
            HTML5<br />CSS3<br />JavaScript<br />jQuery<br />PHP<br />SQL<br />Vue.js<br />Nuxt.js<br />React<br />Ruby(Ruby
            on Rails)<br />
          </dd>
        </dl>
        <dl>
          <dt>開発環境</dt>
          <dd>Docker<br />Git<br />VScode<br />Gulp<br /></dd>
        </dl>
        <dl>
          <dt>その他</dt>
          <dd>
            WordPress<br />PostCSS<br />WebPack<br />TypeScript<br />MicroCMS<br />Slack<br />
          </dd>
        </dl>
      </div>
    </section>
    <section class="works" id="works">
      <div class="inner">
        <h2 class="heading">WORKS</h2>
        <p class="works__notice">
          一部認証のかかっているページはこちらのID・PWをご利用くださいませ。<br />ID:
          gmoam<br />PW: test
        </p>
        <h3 class="heading--sub">Coding<span>コーディングのお仕事</span></h3>
        <ul class="works__list">
          <li>
            <div class="works__list__content">
              <h4>indeed</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>WordPress HTML5 CSS3 PHP JS</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>indeed採用サイト</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>２名 / 1ヶ月</dd>
              </dl>
              <a href="https://jp.indeed.jobs/" rel="noreferrer" target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-01.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>セブンイレブン</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>HTML5 CSS3 PHP JS</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>オーナー募集サイト</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>2名 / 1ヶ月</dd>
              </dl>
              <a
                href="https://www.sej.co.jp/owner/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-02.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>ミニストップ</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>WordPress HTML5 CSS3 PHP JS</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>オーナー募集サイト</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 1ヶ月</dd>
              </dl>
              <a
                href="https://www.ministop-fc.com/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-03.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>川崎競馬</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>WordPress HTML5 CSS3 PHP JS</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>本サイト</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>4名 / 1ヶ月</dd>
              </dl>
              <a
                href="https://www.kawasaki-keiba.jp/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-04.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>キョードー東京</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>WordPress HTML5 CSS3 PHP JS</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>シネオケ特別サイト</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a href="https://cineoke.info/" rel="noreferrer" target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-06.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>GMO アドマーケティング</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>WordPress HTML5 CSS3 PHP JS</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>自社コンテンツポータルサイト</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>２名 / 1ヶ月</dd>
              </dl>
              <a href="http://gmo-am.jp/" rel="noreferrer" target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-07.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>GMO TAXEL</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>WordPress HTML5 CSS3 PHP JS</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>自社プロダクトサイト</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / ２週間</dd>
              </dl>
              <a href="https://taxel.media/" rel="noreferrer" target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-08.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>GMO NIKKO</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>WordPress HTML5 CSS3 PHP JS</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>採用サイト</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / ２週間</dd>
              </dl>
              <a
                href="https://www.koukoku.jp/recruit/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-09.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>チャージスポット</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>HTML5 CSS3 PHP JS</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>キャンペーンページ</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 1週間</dd>
              </dl>
              <a
                href="http://seisaku.gmo-am.jp/test/spot/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-16.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>ザオバ</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>WordPress HTML5 CSS3 PHP JS</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>コーポレートサイト</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 1ヶ月</dd>
              </dl>
              <a href="https://zaoba.co.jp/" rel="noreferrer" target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-12.png" alt="" />
          </li>
        </ul>
        <h3 class="heading--sub">Other<span>学習のために作ったもの</span></h3>
        <ul class="works__list">
          <li>
            <div class="works__list__content">
              <h4>マツコデラックスチャットボット</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>Vue.js</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>勉強のために作ったチャットボットです。</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2日</dd>
              </dl>
              <a
                href="https://festive-khorana-7af813.netlify.app/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img
              src="https://d33wubrfki0l68.cloudfront.net/60acc9a0976d9200071a1dfe/screenshot_2021-05-25-09-56-05-0000.png"
              alt=""
            />
          </li>
          <li>
            <div class="works__list__content">
              <h4>神経衰弱アプリ</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>Vue.js</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>勉強のために作ったゲームアプリです。</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2日</dd>
              </dl>
              <a
                href="https://peaceful-bhabha-851bc3.netlify.app/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img
              src="https://d33wubrfki0l68.cloudfront.net/60b480080fe9d7000770e39d/screenshot_2021-05-31-06-19-57-0000.png"
              alt=""
            />
          </li>
          <li>
            <div class="works__list__content">
              <h4>Vue ToDoアプリ</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>Vue.js TypeScript</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>勉強のために作ったToDoアプリです。</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2日</dd>
              </dl>
              <a
                href="https://unruffled-nobel-1b3713.netlify.app/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img
              src="https://d33wubrfki0l68.cloudfront.net/60a236477a4e1a0007409e56/screenshot_2021-05-17-09-24-52-0000.png"
              alt=""
            />
          </li>
          <li>
            <div class="works__list__content">
              <h4>ハンターハンターキャラクター診断</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>JavaScript</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>勉強のために作った診断コンテンツです。</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2日</dd>
              </dl>
              <a
                href="https://pedantic-kalam-d23ea7.netlify.app/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/mysite-01.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>micro CMSで作成したカフェサイト</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>Vue Nuxt TypeScript</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 4日</dd>
              </dl>
              <a
                href="https://confident-murdock-7f16d7.netlify.app/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img
              src="https://d33wubrfki0l68.cloudfront.net/60a23545e1207c0007d43ce8/screenshot_2021-05-17-09-20-28-0000.png"
              alt=""
            />
          </li>
          <li>
            <div class="works__list__content">
              <h4>ツイッター風アプリケーション</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>Ruby on Rails</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>
                  ツイッター風のアプリケーションを作成しました。(ローカルでの開発)
                </dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2日</dd>
              </dl>
              <a
                href="https://github.com/michinari-sasaki/rails-twitter-clone"
                rel="noreferrer"
                target="_blank"
                >GitHub</a
              >
            </div>
            <img src="../assets/img/mysite-03.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>デザインストック アプリケーション</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>PHP</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>
                  お気に入りのサイトを登録してSlackで共有するアプリケーションです。
                </dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="http://seisaku.gmo-am.jp/test/stock/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-11.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>このポートフォリオサイトです。</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>Vue Nuxt</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2日</dd>
              </dl>
              <a
                href="https://github.com/michinari-sasaki/vue-portfolio"
                rel="noreferrer"
                target="_blank"
                >GitHub</a
              >
            </div>
            <img src="../assets/img/mysite-02.png" alt="" />
          </li>
        </ul>
        <h3 class="heading--sub">Design<span>デザインのお仕事</span></h3>
        <ul class="works__list">
          <li>
            <div class="works__list__content">
              <h4>千住金属</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>デザインのみ</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>リクルートの採用ページ</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 1週間</dd>
              </dl>
              <a
                href="http://seisaku.gmo-am.jp/test/senju/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-10.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>KTX</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>HTML5 CSS3 JS</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>デザインとコーディングを担当しました。</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="http://seisaku.gmo-am.jp/test/ktx/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-14.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>WOWOW シネフィル</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>HTML5 CSS3 JS</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>シネフィルのキャンペーンページです。</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 1週間</dd>
              </dl>
              <a
                href="http://seisaku.gmo-am.jp/test/imagica-lp/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-15.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>スカパー ディズニーチャンネル</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>HTML5 CSS3 JS</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>スカパーのキャンペーンページです。</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 1週間</dd>
              </dl>
              <a
                href="http://seisaku.gmo-am.jp/test/disney_1806/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-17.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>ヘルプマン</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>HTML5 CSS3 JS</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>介護系のLPを作成しました。</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 1週間</dd>
              </dl>
              <a
                href="http://seisaku.gmo-am.jp/test/helpman/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-18.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>電子書籍サイトランキング</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>HTML5 CSS3 JS</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>サイトクローズのため画像のみの掲載です。</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="http://seisaku.gmo-am.jp/test/hikaku/"
                rel="noreferrer"
                target="_blank"
                >サイトを見る</a
              >
            </div>
            <img src="../assets/img/tmb-19.png" alt="" />
          </li>
        </ul>
        <h3 class="heading--sub">Movie<span>動画のお仕事</span></h3>
        <ul class="works__list">
          <li>
            <div class="works__list__content">
              <h4>タウンWi-Fiアプリ PR動画</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>AfterEffects PremierePro</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>デザイン、動画制作を担当</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="https://youtu.be/giKSqY04fds"
                rel="noreferrer"
                target="_blank"
                >動画を見る</a
              >
            </div>
            <img src="../assets/img/movie-22.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>GMO ReeMo PR動画</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>AfterEffects PremierePro</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>デザイン、動画制作を担当</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="https://youtu.be/TRNDrAFuuwM"
                rel="noreferrer"
                target="_blank"
                >動画を見る</a
              >
            </div>
            <img src="../assets/img/movie-25.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>美甘麗茶 販促用動画</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>AfterEffects PremierePro</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>デザイン、動画制作を担当</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="https://youtu.be/FOoBbCIcnB4"
                rel="noreferrer"
                target="_blank"
                >動画を見る</a
              >
            </div>
            <img src="../assets/img/movie-02.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>神アプリ 販促用動画</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>AfterEffects PremierePro</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>デザイン、動画制作を担当</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="https://youtu.be/GM3oIDTFAho"
                rel="noreferrer"
                target="_blank"
                >動画を見る</a
              >
            </div>
            <img src="../assets/img/movie-03.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>ひかり法律事務所 PR動画</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>AfterEffects PremierePro</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>デザイン、動画制作を担当</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="https://youtu.be/Er5k6GdQBns"
                rel="noreferrer"
                target="_blank"
                >動画を見る</a
              >
            </div>
            <img src="../assets/img/movie-04.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>ピンキープラス 販促用動画</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>AfterEffects PremierePro</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>デザイン、動画制作を担当</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="https://youtu.be/mtA5RbeyvG4"
                rel="noreferrer"
                target="_blank"
                >動画を見る</a
              >
            </div>
            <img src="../assets/img/movie-05.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>NuleNuleリップ 販促用動画</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>AfterEffects PremierePro</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>デザイン、動画制作を担当</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="https://youtu.be/R9vufklxqAI"
                rel="noreferrer"
                target="_blank"
                >動画を見る</a
              >
            </div>
            <img src="../assets/img/movie-07.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>販促用テンプレート動画</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>AfterEffects PremierePro</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>デザイン、動画制作を担当</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="https://youtu.be/Y8pUmNGNjUQ"
                rel="noreferrer"
                target="_blank"
                >動画を見る</a
              >
            </div>
            <img src="../assets/img/movie-26.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>Qutt-Tea 販促用動画</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>AfterEffects PremierePro</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>デザイン、動画制作を担当</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="https://youtu.be/cxq3RdBeO-o"
                rel="noreferrer"
                target="_blank"
                >動画を見る</a
              >
            </div>
            <img src="../assets/img/movie-10.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>化粧品 サンプル動画</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>AfterEffects PremierePro</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>デザイン、動画制作を担当</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="https://youtu.be/PATdNC7DvjE"
                rel="noreferrer"
                target="_blank"
                >動画を見る</a
              >
            </div>
            <img src="../assets/img/movie-11.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>フルーツ青汁 販促用動画</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>AfterEffects PremierePro</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>デザイン、動画制作を担当</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="https://youtu.be/st9gM0Mf94c"
                rel="noreferrer"
                target="_blank"
                >動画を見る</a
              >
            </div>
            <img src="../assets/img/movie-12.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>フルーツ青汁 販促用動画</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>AfterEffects PremierePro</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>デザイン、動画制作を担当</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="https://youtu.be/eAUeqBilJQ0"
                rel="noreferrer"
                target="_blank"
                >動画を見る</a
              >
            </div>
            <img src="../assets/img/movie-13.png" alt="" />
          </li>
          <!-- <li>
            <div class="works__list__content">
              <h4>メビウス 販促用動画</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>AfterEffects PremierePro</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>デザインと動画制作を担当しました。</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="https://youtu.be/CobSuj4Ay5Y"
                rel="noreferrer"
                target="_blank"
                >動画を見る</a
              >
            </div>
            <img src="../assets/img/movie-19.png" alt="" />
          </li>
          <li>
            <div class="works__list__content">
              <h4>ピンキープラス 販促用動画</h4>
              <dl>
                <dt>使用技術</dt>
                <dd>AfterEffects PremierePro</dd>
              </dl>
              <dl>
                <dt>説明</dt>
                <dd>デザインと動画制作を担当しました。</dd>
              </dl>
              <dl>
                <dt>人数/工数</dt>
                <dd>1名 / 2週間</dd>
              </dl>
              <a
                href="https://youtu.be/3YrIQJQOhgs"
                rel="noreferrer"
                target="_blank"
                >動画を見る</a
              >
            </div>
            <img src="../assets/img/movie-21.png" alt="" />
          </li> -->
        </ul>
      </div>
    </section>
    <footer class="footer" id="contact">
      <h2 class="heading">CONTACT</h2>
      <p class="footer__mail">bdttb5369@gmail.com</p>
    </footer>
    <div id="root"></div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
