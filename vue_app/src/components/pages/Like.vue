<template>
  <div class="recruit-wrapper">
    <router-link to="/recruit/detail/">
      <div class="recruit-content">
        <div class="recruit-topbox">
          <div class="create-time">2020年4月12日</div>
          <div class="create-work">業務委託</div>
          <div class="matching-status">マッチング率22%</div>
        </div>
        <div class="recruit-centerbox">
          <div class="recruit-title-box">
            【AI・クローラーエンジニア】HR Tech業界で人材と企業を独自のアルゴリズムで結び付け、新たな理論を創ったプラットフォームサービス 一緒に将来を担っていけるメンバーを募集します！
          </div>
          <div class="recruit-company-box">
            株式会社エイト
          </div>
        </div>
        <div class="recruit-btmbox">
          <div class="recruit-detail-box">
            <div class="money-area">
              <div class="money-logo"><font-awesome-icon icon="yen-sign" class="awesome-icon"/></div>
              <div class="money-content">70万 ~ 80万</div>
            </div>
            <div class="location-area">
              <div class="location-logo"><font-awesome-icon icon="map-marker-alt" class="awesome-icon"/></div>
              <div class="location-content">東京都 渋谷区</div>
            </div>
          </div>
          <div class="recruit-skill-box">
            <div class="skill-logo">スキル</div>
            <div class="skill-content">PHP Laravel  Python JavaScript Vue.js</div>
          </div>
          <div class="recruit-sales-box">
            <div class="sales-logo"></div>
            <div class="sales-name">SAMPLE NAME</div>
          </div>
        </div>
      </div>
    </router-link>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
/* Router URL textdecoration 削除 */
a{
  text-decoration: none;
}

.recruit-wrapper{
  width: 92%;
  height: 120%;
  margin: 22px auto;
}

/* 求人content CSS */
.recruit-content{
  width: calc(100% - 20px);
  height: 200px;
  background-color: #FFFFFF;
  box-shadow: 10px 5px 5px grey;
  padding: 20px;
  margin: 15px 0;
  cursor: pointer;
  box-shadow: 0 0 3px 0 rgba(0,0,0,.12), 0 2px 3px 0 rgba(0,0,0,.22);
	transition: .3s;
}
/* Top BOX */
.recruit-topbox{
  width: 100%;
  height: 30px;
}
.create-time{
  color: #818181;
  font-size: 12px;
  display: inline-block;
}
.create-work{
  display: inline-block;
  width: 8%;
  background-color: #f09819;
  color: #FFFFFF;
  border-radius: 12px;
  padding: 5px 12px;
  font-size: 12px;
  text-align: center;
  border: solid 1px #f09819;
}
.matching-status{
  float: right;
  width: 12%;
  background-color: #ffffff;
  color: #1f5abc;
  border-radius: 12px;
  padding: 5px 12px;
  font-size: 12px;
  text-align: center;
  border: solid 1px #1f5abc;
}


/* Center BOX */
.recruit-centerbox{
  width: 100%;
  height: 110px;
}
.recruit-title-box{
  width: calc(100% - 10px);
  height: 60px;
  padding: 15px 5px 0px 5px;
  color: #506690;
  font-size: 16px;
}
.recruit-company-box{
  font-size: 12px;
  color: #818181;
}


/* Bottom BOX */
.recruit-btmbox{
  width: 100%;
  height: 75px;
}
/* 単価 / 勤務地 CSS */
.recruit-detail-box{
  width: 80%;
  height: 40px;
}
.money-area{
  display: inline-block;
  position: relative;
  width: 400px;
}
.location-area{
  display: inline-block;
}
.money-logo{
  width: 25px;
  height: 25px;
  border-radius: 50%;
  display: inline-block;
}
.money-content{
  font-size: 14px;
  display: inline-block;
  position: absolute;
  top: 7px;
  color: #818181;
}

.location-area{
  display: inline-block;
  position: relative;
  width: 400px;
}
.location-logo{
  width: 25px;
  height: 25px;
  border-radius: 50%;
  display: inline-block;
}
.location-content{
  font-size: 14px;
  display: inline-block;
  position: absolute;
  top: 7px;
  color: #818181;
}

/* スキル CSS */
.recruit-skill-box{
  width: 80%;
  /* height: 40px; */
  display: inline-block;
}
.skill-logo{
  width: 120px;
  height: 20px;
  background-color: #2AC1DF;
  color: #FFFFFF;
  text-align: center;
  border-radius: 12px;
  font-size: 14px;
  padding: 2px 0 0 0 ;
  display: inline-block;
}
.skill-content{
  display: inline-block;
  color: #818181;
  font-size: 14px;
}

/* 営業 CSS */
.recruit-sales-box{
  display: inline-block;
  position: relative;
  width: 210px;
}
.sales-logo{
  width: 25px;
  height: 25px;
  border-radius: 50%;
  background-color: grey;
  display: inline-block;
}
.sales-name{
  display: inline-block;
  position: absolute;
  top: 5px;
  margin-left: 5px;
  color: #818181;
}

/* Icon  */
.awesome-icon{
  color: #2AC1DF;
  height: 30px;
}

/* Action アクション*/
.recruit-content:hover{
  opacity: 0.8;
  box-shadow: 0 15px 30px -5px rgba(0,0,0,.15), 0 0 5px rgba(0,0,0,.1);
	transform: translateY(-4px);
}


/* レスポンシブ デザイン */
@media screen and (max-width: 767px) {
  .recruit-wrapper{
    width: 90%;
    margin: 0 auto;
  }
  .recruit-content{
    width: 300px;
  }
  .recruit-topbox{
    width: 100%;
  }
  .create-time{
    font-size: 11px;
  }
  .create-work{
    width: 20%;
  }
  .matching-status{
    
  }
  .recruit-centerbox{
    width: 100%;
    height: 60%;
    position: relative;
  }
  .recruit-title-box{
    font-size: 14px;
  }
  .recruit-company-box{
    position: absolute;
    bottom: 0;
  }
  .recruit-btmbox{
    width: 100%;
    height: 30%;
  }
  .recruit-detail-box{
    width: 100%;
  }
  .money-area{
    width: 49%;
    font-size: 9px;
    display: inline-block;
  }
  .location-area{
    width: 49%;
    font-size: 9px;
    display: inline-block;
  }
  .recruit-skill-box{
    width: 100%;
    height: 30%;
  }
  .skill-logo{
    width: 20%;
    font-size: 11px;
    height: 90%;
  }
  .skill-content{
    font-size: 11px;
  }
  .recruit-sales-box{
    display: none;
  }

}

</style>

