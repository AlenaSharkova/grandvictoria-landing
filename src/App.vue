<template>
  <div class="body">
    <header>
      <div class="headerBlock">
        <img class="header__logo" src="@/assets/logo.png">    
        <nav class="header__nav">
          <li class="nav__item">
            <a href="#home">Главная</a>
          </li>
          <li class="nav__item">
            <a href="#about">О комлексе</a></li>
          <li class="nav__item">
            <a href="#advantages">Преимущества</a>
          </li>
          <li class="nav__item">
            <a href="#infrastructure">Инфраструктура</a>
          </li>
          <li class="nav__item">
            <a href="#conditions">Условия приобретения</a>
          </li>
          <li class="nav__item">
            <a href="#layouts">Типовые планировки</a>
          </li>
          <li class="nav__item">
            <a href="#gallery">Галерея</a>
          </li>
          <li class="nav__item">
            <a href="#progress">Ход строительства</a>
          </li>
          <li class="nav__item">
            <a href="#stock">Акции</a>
          </li>
          <li class="nav__item">
            <a href="#news">Новости</a>
            </li>
        </nav>
        <div class="header__contacts">
          <div class="contacts__title">Отдел продаж:</div>
          <div class="contacts__item">
            <img class="geo__icon" src="@/assets/locationIcon.svg">
            <div class="geo__text contacts__item-text">
              г. Нур-Султан, пересечение ул. С. Нурмағамбетова и Ж.Нажімеденова
            </div>
          </div>
          <div class="contacts__item">
            <img class="tel__icon" src="@/assets/phoneIcon.svg">
            <div class="tel__text contacts__item-text">
              <a href="tel:+7 7172 77-77-77">+7 7172 77-77-77</a>
            </div>
          </div>
          <div class="header__backCall">
            <a href="#">Заказать обратный звонок</a>
          </div>
          <div class="header__insta">
            <a href="https://www.instagram.com/m2group_kz/">
              <img src="@/assets/insta.svg">
            </a>
          </div>
        </div>
      </div>
    </header>

    <main>
      <div class="mainTop">
        <ul class="mainTop__list">
          <li class="mainTop__item">
            <a href="#">Офисы</a>
            </li>
          <li class="mainTop__item">
            <a href="#">Паркинги</a>
          </li>
          <li class="mainTop__item">
            <a href="#">Келлеры</a>
          </li>
        </ul>
        <div class="mainTop__download">
          <a href="#">Скачать презентацию</a>      
          </div>
      </div>

      <section class="home" id="home">
        <img class="home__img" src="@/assets/groupHouses.jpg">
        <img class="home__logo logo-one" src="@/assets/logoHome.png">
        <img class="home__logo logo-two" src="@/assets/logoHome.png">
        <img class="home__logo logo-three" src="@/assets/logoHome.png">
        <img class="home__logo logo-four" src="@/assets/logoHome.png">
        <button class="home__btn">Выбрать квартиру</button>
      </section>

      <section class="about" id="about">
        <div class="about__marker sec-marker"></div>  
        <div class="about__title sec-title">О комплексе</div>
        <div class="aboutBlock">
          <div class="about__text">«Grand Victoria» — это современный, стильный и  яркий  жилой  комплекс,  сочетающий  в  себе  комфорт, функциональность  и  красоту.  Высокий уровень жизни в ЖК «Grand Victoria» обеспечивается за счёт качества строительства,  продуманных  архитектурных  решений,  транспортной  доступности  и  развитой  инфраструктуры. Объект возводится  в  престижном  и  уютном  микрорайоне  столицы,  на  пересечении  улиц  С. Нурмагамбетова  и 
            Ж. Нажимеденова,  в  непосредственной  близости  к  значимым  культурным  объектам  Нур-Султана.  Рядом  находятся мечеть  «Хазрет  Султан»,  Национальный  музей  Республики Казахстан,  Дворец творчества «Шабыт»,  Казахский Государственный академический музыкально-драматический театр им. К. Куанышбаева, монумент «Қазақ Елі». В шаговой доступности несколько государственных и частных школ и детских садов</div>
          <div class="about__infoList">
            <div class="info__item">
              <div class="info__item__num">4</div>
              <div class="info__item__name">дома</div>
            </div>
            <div class="info_line"></div>
            <div class="info__item">
              <div class="info__item__num">9</div>
              <div class="info__item__name">этажей</div>
            </div>
            <div class="info_line"></div>
            <div class="info__item">
              <div class="info__item__num">1040</div>
              <div class="info__item__name">квартир</div>
            </div>
            <div class="info_line"></div>
            <div class="info__item">
              <div class="info__item__num">2023 г.</div>
              <div class="info__item__name">сдача в эксплуатацию</div>
            </div>
          </div>  
        </div>
      </section>

      <section class="advantages" id="advantages">
        <div class="advantages__marker sec-marker"></div>
        <div class="advantages__title sec-title">Преимущества</div>
        <div class="advantagesBlock">
          <div class="advantages__mainItem">
            <div class="item__mainPhoto">
              <img src="@/assets/advantagesMainPhoto.jpg" alt="Карта местоположения комплекса">
            </div>
            <div class="item__content">
              <div class="item-title">Локация</div>
              <div class="item-text">
                Жилой комплекс «Grand Victoria» расположен в самом сердце культурной жизни столицы. Не нужно далеко ехать, чтобы посетить мечеть, театр, музей или концертный зал – всё это в шаговой доступности.
              </div>
            </div>
          </div>
          <div class="advantagesList">
            <div class="advantages__firstColumn">
              <div class="firstColumn__item" v-for="item in first_column" :key="item.id">
                <div class="item__photo">
                  <img :src="require(`@/assets/${item.photo_url}`)" alt="Карта местоположения комплекса">
                </div>
                <div class="item__content">
                  <div class="item-title">{{ item.title }}</div>
                  <div class="item-text">{{ item.text }}</div>
                </div>
              </div>
            </div>
            <div class="advantages__secondColumn">
              <div class="secondColumn__item" v-for="item in second_column" :key="item.id">
                <div class="item__content">
                  <div class="item-title">{{ item.title }}</div>
                  <div class="item-text">{{ item.text }}</div>
                </div>
                <div class="item__photo">
                  <img :src="require(`@/assets/${item.photo_url}`)" :alt=item.alt>
                </div>
              </div>
            </div>

          </div>
        </div>
      </section>

      <section class="infra" id="infrastructure">
        <div class="infra__marker sec-marker"></div>
        <div class="infra__title sec-title">Инфраструктура</div>
        <div class="infraBlock">
          <div class="infra__menu">
            <div class="menu__item active" @click="id=0">Расположение</div>
            <div class="menu__item" v-show="visible" @click="id=1">Все продумано</div>
            <div class="menu__item" v-show="visible" @click="id=2">Безопасный двор</div>
          </div>
          <div class="infra__contentBlock" v-for="(item, index) in infra_content" :key="item.id">
            <div class="infra__content__item" v-if="index == id">  
              <div class="content__text">{{ item.text }}</div>
              <div class="content__img">{{ item.img }}</div>
            </div>
          </div>

          <div class="swiper infraSwiper">
            <!-- Additional required wrapper -->
            <div class="swiper-wrapper">
              <!-- Slides -->
              <div class="infra__content__item">Slide 1</div>
              <div class="infra__content__item">Slide 2</div>
              <div class="infra__content__item">Slide 3</div>
              
            </div>
            <!-- If we need pagination -->
            <div class="swiper-pagination"></div>

          </div>
        </div>
      
      
      </section>
    </main>
  </div>
</template>

<script>
import Swiper, {Navigation, Pagination} from 'swiper';

const swiper = new Swiper('.swiper', {
  spaceBetween: 30,
  modules:[Navigation, Pagination],
  // Optional parameters
  direction: 'vertical',
  loop: true,

  //If we need pagination
  pagination: {
    el: ".swiper-pagination",
    clickable: true,
    renderBullet: function (index, className) {
      return '<span class="' + className + '">' + (index + 1) + "</span>";
    },
  },
})


export default {
  name: 'App',
  components: {
  },
  data: () => ({
    id: 0,
    visible: true,


    first_column: [
      {
        title: 'Разумные метры',
        text: 'При проектировании квартир ЖК «Grand Victoria» использовался принцип «Разумные метры», который позволил эффективно использовать каждый квадратный метр площади. Все планировки функциональны - нет слишком длинных коридоров, тупиков и тёмных углов. Рациональные, эргономичные и продуманные планировки позволят функционально разместить мебель и сделать пространство комфортным',
        photo_url: 'advantages1.jpg',
        alt: 'Диван с кухней на заднем фоне'
      },
      {
        title: 'Технология строительства',
        text: 'Проект возводится по уникальному методу индустриального строительства. Все изделия выпускаются в заводских условиях - ровные стены, готовые под оклейку обоями или покраску с проведеннымии каналами для электропроводки, трехслойные наружные фасады, отвечающие всем стандартам качества, безопасности и архитектурной эстетики. Учитывая климатические условия столицы от -40 до +40 ⁰С, изделия обладают повышенной энергоэффективностью и влагонепроницаемостью.',
        photo_url: 'advantages2.jpg', 
        alt: 'Стена дома в разрезе'
      },
      {
        title: 'Паркинг',
        text: 'Подземный паркинг с автоматизированным контролем доступа. Он оборудован системами видеонаблюдения, вентиляции и дымоудаления. Подземный паркинг рассчитан на 358 машиномест. Также имеются специальные парковочные места для водителей с ограниченными возможностями. Предусмотрено также 16 мотомест. Есть отдельная парковка для гостевых автомобилей.',
        photo_url: 'advantages3.jpg',
        alt: 'Просторная парковка'
      },
    ],
    second_column: [
      {
        title: 'Идеальные планировки',
        text: 'В проекте предусмотрены квартиры различной комнатности от 44 до 117 квадратных метров. Компактные однушки станут отличным вариантом для тех, кто ещё не обзавёлся семьёй. Функциональные двухкомнатные квартиры подойдут молодым парам, а для семей с детьми запроектированы просторные трёхкомнатные и четырёхкомнатные квартиры с большими площадями',
        photo_url: 'advantages4.jpg', 
        alt: 'Радостная семья в квартире'
      },
      {
        title: 'Стильные решения',
        text: 'Входные группы, лифтовые зоны, колясочные и другие общественные пространства комплекса не только функциональны, но и выполнены в современном стиле.  Перед лифтами предусмотрены указатели этажей, а также информационные стенды, для того, что бы быть в курсе жизни комплекса.',
        photo_url: 'advantages5.jpg',
        alt: 'Яркая парадная'
      },
      {
        title: 'Келлеры',
        text: 'Для оптимизации пространства квартир в паркинге  предусмотрены помещения для хранения - келлеры. Келлерная система хранения популярна в Европе. Не нужно хранить межсезонные вещи, спортинвентарь, инструменты, туристические принадлежности на балконе или в доме. В келлерах можно организовать постоянное или временное хранение вещей.',
        photo_url: 'advantages6.jpg',
        alt: 'Келлер с велосипедом и вещами на полках'
      },
    ],

    infra_content: [
      {
        text: 'text1',
        img: 'img1',
      },
      {
        text: 'text2',
        img: 'img2',
      },
      {
        text: 'text3',
        img: 'img3',
      }
    ]  
  }),
}
</script>

<style lang="scss">
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
a {
  text-decoration: none;
  color: #000;
}
.body {
  font-family: 'Montserrat';
  font-style: normal;

  header {
    left: 0;
    top: 0;
    height: 100vh;
    width: 260px;
    position: fixed;
    z-index: 10;
    box-shadow: 2px 0px 6px rgba(91, 91, 91, 0.1);
    background-color: #FFFFFF;
    
    .headerBlock {
      height: 100%;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .header__logo {
      margin: 21px 44px 0;
      max-height: 117px;
      max-width: 172px; 
    }
    .header__nav {
      //margin-top: 48px;
      list-style-type: none;

      .nav__item {
        position: relative;
        font-weight: 400;
        font-size: 16px;
        line-height: 20px;
        padding-left: 30px;
        &:hover {
          font-weight: 500;
          a {
            color:#E31E24;
          }
          &:after {
            position: absolute;
            content: url(@/assets/litleLogo.svg);
            top: 0;
            left: 10px;
          }
        }
        &:not(:last-child) {
          margin-bottom: 10px;
        }
      }
    }
    .header__contacts {
      margin-bottom: 20px;
      margin-left: 35px;

      .contacts__title {
        margin-bottom: 13px;
      }
      
      .contacts__item {
        display: flex;
        align-items: flex-start;
        margin-bottom: 13px;

        .contacts__item-text {
          padding-left: 9px;
          font-weight: 300;
          font-size: 14px;
          line-height: 17px;
        }
      }
      .header__backCall {
        font-weight: 400;
        font-size: 14px;
        line-height: 17px;
        margin-bottom: 13px;
        &:hover {
          text-decoration-line: underline;
          text-decoration-color: #E31E24;
          a {
            color: #E31E24;
          } 
        }

      }
    }
  }

  main {
    margin-left: 260px;

    .sec-title {
      margin-left: 63px;
      font-family: 'Bebas Neue';
      font-style: normal;
      font-weight: 400;
      font-size: 50px;
      line-height: 50px;
      text-transform: uppercase;
    }
    .sec-marker {
      width: 23px;
      height: 112px;
      position: absolute;
      top: 0;
      left: 0;
      background-color: #fff
    }
  
    .mainTop {
      background-color: #FFFFFF;
      height: 40px;
      display: flex;
      justify-content: space-between;  
      align-items: start;
      max-width: 1180px;
      margin-right: 15px;
      padding-left: 86px;
      font-weight: 400;
      font-size: 16px;
      line-height: 20px;
      padding-top: 10px;
      box-sizing: border-box;

      .mainTop__list {
        display: flex;
        list-style-type: none;

        .mainTop__item {
          margin-right: 40px;
          &:hover {
            border-bottom: 3px solid #E31E24;
          }
        }
      }
      .mainTop__download {
          &:hover {
            border-bottom: 3px solid #E31E24;
          }
      }
    }
    .home {
      position: relative;
      margin-bottom: 86px;

      .home__img {        
        width: 100%;   
        height: 100%;
        display: block;
      }
      .home__logo {
        position: absolute;
        z-index: 9;
      }
      .logo-one {
        top: 17%;
        left: 23%;
      }
      .logo-two {
        top: 4%;
        left: 48%;
      }
      .logo-three {
        top: 13%;
        left: 80%;
      }
      .logo-four {
        top: 42%;
        left: 60%;
      }
      .home__btn {
        cursor: pointer;
        border: 0;
        background-color: #E31E24;
        color: #fff;
        position: absolute;
        bottom: 0;
        left: 111px;
        padding: 18px 82px 18px 16px;
        font-weight: 700;
        font-size: 16px;
        line-height: 20px;
        &::before {
          position: absolute;
          content: url(@/assets/right.svg);
          top: 18px;
          right: 23px;
        }
      }
    }
    .about {
      position: relative;
      margin-bottom: 96px;

      .about__marker {
        background-color: #E31E24;
      }
      .aboutBlock {
        margin-left: 63px;
        margin-right: 88px;

        .about__text {
          margin-top: 36px;
          font-weight: 400;
          font-size: 16px;
          line-height: 20px;
        }
        .about__infoList {
          margin-top: 32px;
          display: flex;
          justify-content: space-between;
          flex-wrap: nowrap;

          .info__item {
            position: relative;
            display: flex;
            flex-direction: column;
            align-items: center;
        
            .info__item__num {
              font-weight: 600;
              font-size: 20px;
              line-height: 24px;
              text-align: center;
              color: #E31E24;
            }
            .info__item__name {
              font-weight: 400;
              font-size: 20px;
              line-height: 24px;
              text-align: center;
            }
          }
          .info_line {
            width: 1px;
            height: 51px;
            background-color: #000;
          }
        }
      }
    }
    .advantages {
      position: relative;

      .advantages__marker {
        background-color: #5B5B5B;
      }

      .advantagesBlock {
        margin-left: 63px;
        margin-right: 88px;

        .item-title {
            font-weight: 500;
            font-size: 20px;
            line-height: 24px;
            color: #000;
            margin-bottom: 24px;
          }
        .item-text {
          font-weight: 400;
          font-size: 16px;
          line-height: 20px;
          color: #000;
        }

        .advantages__mainItem {
          margin-top: 36px;
          position: relative;
          
          .item__mainPhoto {        
            img { 
              display: block; 
              width: 100%; 
            }
          }
          .item__content {
            margin-top: 24px;
            padding-left: 43px;
            position: relative;
            &::before {
              position: absolute;
              content: '';
              width: 1px;
              height: 54px;
              background-color: #e31e24;
              z-index: 2;
              top: -43px;
              left: 32px;
            }
            &::after {
              position: absolute;
              content: url(@/assets/litleLogo.svg);
              top: 2px;
              left: 26px;
            }
          }
        }
        
        .advantagesList {
          display: flex;
          flex-direction: row;
          justify-content: space-between;
          margin-top: 90px;

          .advantages__firstColumn {
            max-width: 475px;

            .firstColumn__item {
              margin-bottom: 70px;

              .item__content {
                margin-top: 24px;
                padding-left: 78px;
                position: relative;
                &::before {
                  position: absolute;
                  content: '';
                  width: 1px;
                  height: 38px;
                  background-color: #e31e24;
                  z-index: -1;
                  top: -29px;
                  left: 66px;
                }
                &::after {
                  position: absolute;
                  content: url(@/assets/litleLogo.svg);
                  top: 2px;
                  left: 60px;
                }
              }
            }
            
          }
          .advantages__secondColumn {
            max-width: 475px;
            .secondColumn__item {
              margin-bottom: 85px;

              .item__content {
                margin-bottom: 24px;
                padding-left: 78px;
                position: relative;
                &::before {
                  position: absolute;
                  content: '';
                  width: 1px;
                  height: 221px;
                  background-color: #e31e24;
                  z-index: -1;
                  top: 11px;
                  left: 66px;
                }
                &::after {
                  position: absolute;
                  content: url(@/assets/litleLogo.svg);
                  top: 2px;
                  left: 60px;
                }
              }
            }
            

            
          }
          

        }
      }
      
    }

    .infra {
      position: relative;

      .infra__marker {
        background-color: #E31E24;
      }
      .infraBlock {
        margin-left: 63px;
        margin-right: 88px;

        .infra__menu {
          display: flex;
          justify-content: start;
          margin-top: 36px;
          margin-bottom: 40px;

          .menu__item {
            margin-right: 40px;
            padding-bottom: 16px;
            cursor: pointer;
          }
          .active {
            border-bottom: 2px solid #E31E24;
          }
        }
        
        .infraSwiper {
          width: 1000px;
          height: 200px;

          .infra__content__item {
            display: flex;
            justify-content: center;
            font-size: 20px;
            text-align: center;
            background: #fff;
          }
          .swiper-pagination-bullet {
            width: 20px;
            height: 20px;
            text-align: center;
            line-height: 20px;
            font-size: 12px;
            color: #000;
            opacity: 1;
            background: rgba(0, 0, 0, 0.2);
          }

          .swiper-pagination-bullet-active {
            color: #fff;
            background: #007aff;
          }
        }
      }
    }
  }
}
</style>
