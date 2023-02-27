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
        <div class="home__backlight backlight-top">
          <img src="https://grandvictoria.kz/wp-content/uploads/2021/12/vector-6.svg">
        </div>
        <div class="home__backlight backlight-left">
          <img src="https://grandvictoria.kz/wp-content/uploads/2021/12/vector-3.svg">
        </div>
        <div class="home__backlight backlight-bottom">
          <img src="https://grandvictoria.kz/wp-content/uploads/2021/12/vector-1.svg">
        </div>
        <div class="home__backlight backlight-right">
          <img src="https://grandvictoria.kz/wp-content/uploads/2021/12/vector-2.svg">
        </div>
        <img class="home__logo logo-one" src="@/assets/logoHome.png">
        <img class="home__logo logo-two" src="@/assets/logoHome.png">
        <img class="home__logo logo-three" src="@/assets/logoHome.png">
        <img class="home__logo logo-four" src="@/assets/logoHome.png">
        <button class="home__btn">Выбрать квартиру</button>
      </section>

      <section class="about" id="about">
        <div class="about__marker sec-marker"></div>
        <h2 class="about__title sec-title">О комплексе</h2>
        <div class="aboutBlock">
          <div class="about__text">«Grand Victoria» — это современный, стильный и  яркий  жилой  комплекс,  сочетающий  
            в  себе  комфорт, функциональность  и  красоту.  Высокий уровень жизни в ЖК «Grand Victoria» обеспечивается 
            за счёт качества строительства,  продуманных  архитектурных  решений,  транспортной  доступности  и  развитой  инфраструктуры. 
            Объект возводится  в  престижном  и  уютном  микрорайоне  столицы,  на  пересечении  улиц  С. Нурмагамбетова  и 
            Ж. Нажимеденова,  в  непосредственной  близости  к  значимым  культурным  объектам  Нур-Султана.  
            Рядом  находятся мечеть  «Хазрет  Султан»,  Национальный  музей  Республики Казахстан,  Дворец творчества «Шабыт»,  
            Казахский Государственный академический музыкально-драматический театр им. К. Куанышбаева, монумент «Қазақ Елі». 
            В шаговой доступности несколько государственных и частных школ и детских садов
          </div>
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
        <h2 class="advantages__title sec-title">Преимущества</h2>
        <div class="advantagesBlock">
          <div class="advantages__mainItem">
            <div class="item__mainPhoto">
              <img src="@/assets/advantagesMainPhoto.jpg" alt="Карта местоположения комплекса">
            </div>
            <div class="item__content">
              <div class="item-title">Локация</div>
              <div class="item-text">
                Жилой комплекс «Grand Victoria» расположен в самом сердце культурной жизни столицы. Не нужно далеко 
                ехать, чтобы посетить мечеть, театр, музей или концертный зал – всё это в шаговой доступности.
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
        <h2 class="infra__title sec-title">Инфраструктура</h2>
        <div class="infraBlock">
          <div class="swiper infraSwiper">
            <div class="swiper-pagination"></div>
            <!--Slides-->
            <div class="swiper-wrapper">
              <div class="swiper-slide" v-for="infra_item in infra_content" :key="infra_item.id">
                <div class="infra__content__item">
                  <div class="content__text">{{ infra_item.text }}</div>
                  <div class="illustration" v-if="typeof infra_item.illustration == 'string' ">
                    <img class="content__img" :src="require(`@/assets/${infra_item.illustration}`)" :alt=infra_item.alt>
                  </div>
                  <div class="illustrationList__location" v-else-if="typeof infra_item.illustration == 'object' ">
                    <div class="location__item" v-for="loc_item in infra_item.illustration" :key="loc_item.id">
                      <div class="item__img">
                        <img :src="require(`@/assets/${loc_item.img}`)" :alt=loc_item.alt>
                      </div>
                      <div class="item__text" v-html="loc_item.text">
                      </div>
                    </div>
                  </div>  
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="cond" id="conditions">
        <div class="cond__marker sec-marker"></div>
        <h2 class="cond__title sec-title">Условия приобретения</h2>
        <div class="condList">
          <div class="cond__item" v-for="cond_item in condition_list" :key="cond_item">
            <div class="item__icon" v-html="cond_item.icon">
              
            </div>
            <div class="item__content">
              <div class="item__content__text">{{ cond_item.text }}</div>
              <div class="item__content__subtext">{{ cond_item.subtext }}</div>
            </div>
          </div>
        </div>


      </section>

      <section class="vid">
        <div class="vid__marker sec-marker"></div>
        <h2 class="vid__title sec-title">Видеопрезентация</h2>
        <div class="vidBlock">
          <div class="videoPlayer">
            <iframe src="https://www.youtube.com/embed/E23rnQ5vjvQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
          </div>
          <div class="viewButtons">
            <button class="view__btn">Во дворе</button>
            <button class="view__btn">На улице</button>
          </div>
        </div>
      </section>

      <section class="layouts" id="layouts">
        <div class="layouts__marker sec-marker"></div>
        <h2 class="layouts__title sec-title">Типовые планировки</h2>
        <div class="layoutsBlock">
            <div class="swiper layoutsSwiper">
            <div class="swiper-pagination"></div>
            <!--Slides-->
            <div class="swiper-wrapper">
              <div class="swiper-slide" v-for="plan in layouts_content" :key="plan.id">
                <div class="layouts__container__plan">
                  <div class="planContent">
                    <div class="plan__title">{{ plan.title }}</div>
                    <ul class="plan__list">
                      <li class="plan__item" v-for="info in plan.param" :key="info.id">
                        <div class="plan__item__text">{{ info.text }}</div>
                        <div class="plan__item__num">{{ info.num }}</div>
                      </li>
                    </ul>
                    <button class="plan__btn">Получить консультацию</button>
                  </div>
                  <div class="plan__img">
                    <img :src="require(`@/assets/${plan.img}`)" alt="Планировка квартиры">
                  </div>
                </div>
              </div>
            </div>
            <div class="plan__navigation">
              <div class="navigation__vector swiper-button-prev">
                <img src="@/assets/vectorLeft.svg">
              </div>
              <div class="navigation__vector swiper-button-next">
                <img src="@/assets/vectorRight.svg">
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="gallery" id="gallery">
        <div class="gallery__marker sec-marker"></div>
        <h2 class="gallery__title sec-title">Галерея</h2>
        <div class="galleryBlock">
          <div class="swiper gallerySwiper">
            <div class="swiper-wrapper">
              <div class="swiper-slide" v-for="img in gallery" :key="img.id">
                <div class="gallery__img">
                    <img :src="require(`@/assets/${img}`)" alt="Этап строительства">
                </div>
              </div>
            </div>
            <div class="gallery__navigation">
              <div class="navigation__vector swiper-button-prev">
                <img src="@/assets/vectorLeft.svg">
              </div>
              <div class="navigation__vector swiper-button-next">
                <img src="@/assets/vectorRight.svg">
              </div>
            </div>
            <div class="swiper-pagination"></div>
          </div>

        </div>
        

      </section>

      <section class="progress" id="progress">
        <div class="progress__marker sec-marker"></div>
        <h2 class="progress__title sec-title">Ход строительства</h2>
        <div class="progressBlock">
          <div class="swiper progressSwiper">
            <div class="swiper-pagination"></div>
            <div class="swiper-wrapper wrapper__block">
              <div class="swiper-slide slide__block" v-for="block in progress" :key="block.id">
                <div class="swiper progress__subSwiper">
                  <div class="swiper-wrapper subWrapper">
                    <div class="swiper-slide subSlide" v-for="img in block" :key="img.id">
                      <div class="item__img">
                        <img :src="require(`@/assets/${img}`)" alt="Этап строительства">
                      </div>
                    </div>
                  </div>
                  <div class="subSlide__modules" v-if="block.length > 3">
                    <div class="progress__navigation subNavigation">
                      <div class="navigation__vector swiper-button-prev">
                        <img src="@/assets/vectorLeft.svg">
                      </div>
                      <div class="navigation__vector swiper-button-next">
                        <img src="@/assets/vectorRight.svg">
                      </div>
                    </div>
                    <div class="swiper-pagination subPagination"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="news" id="news">
        <div class="news__marker sec-marker"></div>
        <h2 class="news__title sec-title">Новости</h2>
        <div class="newsBlock">
          <div class="news__list">
            <div class="new__item" v-for="new_item in news" :key="new_item.id">
              <div class="new__img">
                <img :src="require(`@/assets/${new_item.img}`)" alt="Картинка к новости">
                <div class="new__date">{{ new_item.date }}</div>
              </div>
              <div class="new__text">{{ new_item.text }}</div>
            </div>
          </div>
          <div class="news__additions">
            <a href="#">Все новости</a>
          </div>
        </div>
      </section>

      <section class="consulta">
        <div class="consultaBlock">
          <div class="consulta__title">Получите консультацию</div>
          <div class="consulta__data">
            <div class="data-name consulta__form">
              <div class="name__text">Имя</div>
              <input type="text" name="your-name" value sive="40" placeholder="Введите имя">
            </div>
            <div class="data-tel consulta__form">
              <div class="tel__text">Телефон</div>
              <input type="tel" name="your-tel" value sive="40" placeholder="+ 7">
            </div>
            <button class="data__send">Получить консультацию</button>
          </div>
          <div class="consulta__subtext">Нажимая кнопку “Получить консультацию”, вы соглашаетесь с условиями обработки личных данных</div>
        </div>
      </section>

      <section class="map">
        <div class="mapBlock">
          <iframe src="https://yandex.ru/map-widget/v1/?um=constructor%3A115ff9e58fbc163b3a52ccf039779ff7bb381ea051f28bf74bde31c3112a0baf&amp;source=constructor" frameborder="0"></iframe>
        </div>
        <div class="map__contacts">
          <div class="contacts__title">Отдел продаж:</div>
          <div class="contacts__item geo-item">
            <img class="geo__icon" src="@/assets/locationIcon.svg">
            <div class="geo__text contacts__item-text">
              г. Нур-Султан, <br>пересечение ул. С. Нурмағамбетова и Ж.Нажімеденова
            </div>
          </div>
          <div class="contacts__item">
            <img class="tel__icon" src="@/assets/phoneIcon.svg">
            <div class="tel__text contacts__item-text">
              <a href="tel:+7 7172 77-77-77">+7 7172 77-77-77</a>
            </div>
          </div>
        </div>
      </section>

      <div class="footer">
        <div class="footerBlock">
          <div class="footer__copy">© 2021 ЖК «Grand Victoria»</div>
          <div class="footer__info">Реализация квартир, офисов и парковочных мест производится в соответствии с Законом Республики Казахстан 
            от 7 апреля 2016 года № 486-V «О долевом участии в жилищном строительстве».</div>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
import Swiper, {Navigation, Pagination} from 'swiper';
import 'swiper/css'


export default {
  name: 'App',
  components: {},
  data: () => ({
    id: 0,
    visible: true,
    swiper: '',


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
        text: 'Жилой комплекс «Grand Victoria» расположен в самом сердце культурной жизни столицы. Не нужно далеко ехать, чтобы посетить мечеть, театр, музей, концертный зал или знаковый городской монумент – всё это в шаговой доступности. Лучшие достопримечательности Нур-Султана можно видеть каждый день, устраивая неспешные прогулки.',
        illustration: [
          {
            img: 'location1.jpg',
            alt: 'Казахский драматический театр',
            text: '220 м. до Казахского драматического театра',
          },
          {
            img: 'location2.jpg',
            alt: 'Мечеть «Хазрет-Султан»',
            text: 'Вид из окон на мечеть «Хазрет-Султан»',
          },
          {
            img: 'location3.jpg',
            alt: 'Национальный музей Республики Казахстан',
            text: '5 мин. до Национального музея Республики Казахстан',
          },
          {
            img: 'location4.jpg',
            alt: 'Президентский парк',
            text: '1 км. до Президентского <br> парка',
          },
          {
            img: 'location5.jpg',
            alt: 'Дворец творчества «Шабыт»',
            text: '7 мин. ходьбы до Дворца творчества «Шабыт»',
          },
          {
            img: 'location6.jpg',
            alt: 'Монумент «Қазақ Елі»',
            text: '800 м. до монумента  <br> «Қазақ Елі»',
          },
        ],
      },
      {
        text: 'Все квартиры в ЖК «Grand Victoria» сдаются с качественной предчистовой отделкой. Предусмотрено устройство стяжки для полов. В каждой квартире надёжные металлические входные двери с тепло и звукоизоляцией, а также платиковые окна. Выполнена прокладка электросетей. Есть стильные панельные радиаторы отопления. В квартиры заведены системы водопровода и канализации с установкой заглушек, есть точки вывода горячей и холодной воды.',
        illustration: 'infra2.png',
        alt: 'Квартира с указателями на предметы отделки'
      },
      {
        text: 'Двор ЖК «Grand Victoria» оборудован по всем стандартам качества. Оборудованная площадка безопана для отдыха вместе с детьми.',
        illustration: 'infra3.png',
        alt: 'Двор с игровой площадкой'
      }
    ],

    pagination_infra: ['Расположение', 'Все продумано', 'Безопасный двор'],

    condition_list: [
      {
        text: '340 000 тг',
        subtext: 'При 100% оплате',
        icon: '<svg width="59" height="48" viewBox="0 0 59 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M58.8405 29.2315C58.7108 29.0099 58.5114 28.8374 58.2734 28.7411L54.0419 27.009L58.4245 24.4282C58.9786 24.1039 59.1649 23.3919 58.8405 22.8378C58.7108 22.6162 58.5114 22.4437 58.2734 22.3474L54.0419 20.6153L58.4245 18.0346C58.8073 17.8043 59.0242 17.375 58.9825 16.9302C58.9489 16.4909 58.6698 16.1082 58.2618 15.9421L41.6033 9.11829L33.3962 5.63083C33.2629 5.57808 33.1209 5.55062 32.9777 5.54946L19.6091 0.109019C19.2808 -0.0272824 18.9082 -0.00577616 18.5977 0.167144L0.683762 10.2343C0.110366 10.523 -0.120388 11.222 0.168345 11.7954C0.299996 12.0569 0.525664 12.2592 0.800011 12.3616L5.12446 14.1519L0.683762 16.628C0.125042 16.9442 -0.0715635 17.6536 0.244633 18.2123C0.370327 18.4343 0.565334 18.6087 0.800011 18.7088L5.12446 20.499L0.707012 22.9751C0.116324 23.2268 -0.158314 23.9098 0.0933644 24.5003C0.22458 24.8082 0.482071 25.0445 0.800011 25.149L5.12446 26.9276L0.707012 29.4037C0.148292 29.7199 -0.0483138 30.4293 0.267883 30.988C0.393577 31.21 0.588584 31.3844 0.823261 31.4845L15.8542 37.8666C15.9091 37.9066 15.9676 37.9416 16.0286 37.9712L24.2474 41.4587L39.3597 47.8872C39.6997 48.0315 40.0882 48.0057 40.4059 47.8175L58.4245 37.2156C58.9786 36.8913 59.1649 36.1792 58.8405 35.6252C58.7108 35.4036 58.5114 35.2311 58.2734 35.1348L54.0419 33.4026L58.4245 30.8219C58.9786 30.4977 59.1647 29.7856 58.8405 29.2315ZM55.216 23.5914L39.7201 32.7169L25.8632 26.8347V22.9637L39.3481 28.6947C39.4915 28.7557 39.6457 28.7874 39.8015 28.7877C40.0101 28.7877 40.2149 28.7315 40.3943 28.625L51.5193 22.0802L55.216 23.5914ZM55.2625 17.1861L39.7201 26.3116L27.1303 20.9642L41.3127 11.4899L55.2625 17.1861ZM15.2846 35.1233L3.8806 30.2757L7.79818 28.0786L15.2962 31.2638L15.2846 35.1233ZM15.2846 28.7296L3.8806 23.882L7.79818 21.6617L15.2962 24.8469L15.2846 28.7296ZM15.2846 22.3359L3.8806 17.5L7.79818 15.3029L15.2962 18.4881L15.2846 22.3359ZM3.8806 11.1063L19.2487 2.46901L30.3969 7.03759L16.3541 16.4072L3.8806 11.1063ZM24.0498 20.2434C23.7293 20.4599 23.5377 20.8216 23.5383 21.2083V38.6456L17.6212 36.1346V18.3602L33.0242 8.09545L38.7552 10.4204L24.0498 20.2434ZM55.216 36.3788L39.7201 45.4927L25.8632 39.6105V35.751L39.3481 41.424C39.6881 41.5682 40.0765 41.5424 40.3943 41.3542L51.5193 34.8094L55.216 36.3788ZM39.7201 39.099L25.8632 33.2168V29.3573L39.3597 35.0884C39.6997 35.2327 40.0882 35.2068 40.4059 35.0186L51.531 28.4738L55.216 29.9851L39.7201 39.099Z" fill="black"/></svg>',
      },
      {
        text: '360 000 тг',
        subtext: 'В рассрочку',
        icon: '<svg width="64" height="64" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg"> <path d="M31 8V16" stroke="black" stroke-width="2" stroke-miterlimit="5" /> <path d="M31 56V48" stroke="black" stroke-width="2" stroke-miterlimit="5" /> <path d="M55 32H47" stroke="black" stroke-width="2" stroke-miterlimit="5" /> <path d="M7 32H15" stroke="black" stroke-width="2" stroke-miterlimit="5" /> <path d="M47.97 15.03L31 32" stroke="black" stroke-width="2" stroke-miterlimit="5" /><path d="M14.0312 48.97L19.6913 43.31" stroke="black" stroke-width="2" stroke-miterlimit="5" /><path d="M47.9686 48.97L42.3086 43.31" stroke="black" stroke-width="2" stroke-miterlimit="5" /><path d="M14.0312 15.03L19.6913 20.69" stroke="black" stroke-width="2" stroke-miterlimit="5" /> <path d="M31 56C44.2548 56 55 45.2548 55 32C55 18.7452 44.2548 8 31 8C17.7452 8 7 18.7452 7 32C7 45.2548 17.7452 56 31 56Z" stroke="black" stroke-width="2" stroke-miterlimit="5" /> </svg>',
      },
      {
        text: '380 000 тг',
        subtext: 'В рассрочку',
        icon: '<svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg"> <path fill-rule="evenodd" clip-rule="evenodd" d="M45.5282 4.47178C45.935 4.87858 45.935 5.53813 45.5282 5.94492L5.94491 45.5283C5.53811 45.9351 4.87857 45.9351 4.47177 45.5283C4.06497 45.1215 4.06497 44.4619 4.47177 44.0551L44.0551 4.47178C44.4619 4.06499 45.1214 4.06499 45.5282 4.47178Z" fill="black"/> <path fill-rule="evenodd" clip-rule="evenodd" d="M36.4583 27.0833C32.5432 27.0833 29.1667 30.6956 29.1667 35.4167C29.1667 40.1378 32.5432 43.75 36.4583 43.75C40.3735 43.75 43.75 40.1378 43.75 35.4167C43.75 30.6956 40.3735 27.0833 36.4583 27.0833ZM27.0833 35.4167C27.0833 29.7824 31.1687 25 36.4583 25C41.748 25 45.8333 29.7824 45.8333 35.4167C45.8333 41.0509 41.748 45.8333 36.4583 45.8333C31.1687 45.8333 27.0833 41.0509 27.0833 35.4167Z" fill="black"/><path fill-rule="evenodd" clip-rule="evenodd" d="M13.5417 6.25002C9.62655 6.25002 6.25001 9.86225 6.25001 14.5834C6.25001 19.3045 9.62655 22.9167 13.5417 22.9167C17.4568 22.9167 20.8333 19.3045 20.8333 14.5834C20.8333 9.86225 17.4568 6.25002 13.5417 6.25002ZM4.16667 14.5834C4.16667 8.94912 8.25205 4.16669 13.5417 4.16669C18.8313 4.16669 22.9167 8.94912 22.9167 14.5834C22.9167 20.2176 18.8313 25 13.5417 25C8.25205 25 4.16667 20.2176 4.16667 14.5834Z" fill="black"/> </svg>',
      },
    ],

    layouts_content: [
        {
          title: 'Вариант 1',
          param: [
            {
              text: 'Пятно',
              num: '1, 2, 3, 4'
            },
            {
              text: 'Этажи',
              num: '2-9'
            },
            {
              text: 'Комнат',
              num: '1'
            },
            {
              text: 'Площадь',
              num: '44,10'
            },{
              text: 'Кухня',
              num: '12,46'
            },
          ],
          img: 'plan1.png'
        },
        {
          title: 'Вариант 2',
          param: [
            {
              text: 'Пятно',
              num: '1, 2, 3, 4'
            },
            {
              text: 'Этажи',
              num: '2-9'
            },
            {
              text: 'Комнат',
              num: '2'
            },
            {
              text: 'Площадь',
              num: '64,16'
            },{
              text: 'Кухня',
              num: '12,46'
            },
          ],
          img: 'plan2.png'
        },
        {
          title: 'Вариант 3',
          param: [
            {
              text: 'Пятно',
              num: '2, 4'
            },
            {
              text: 'Этажи',
              num: '2-9'
            },
            {
              text: 'Комнат',
              num: '3'
            },
            {
              text: 'Площадь',
              num: '84,73'
            },{
              text: 'Кухня',
              num: '17,19'
            },
          ],
          img: 'plan3.png'
        },
        {
          title: 'Вариант 4',
          param: [
            {
              text: 'Пятно',
              num: '1, 4'
            },
            {
              text: 'Этажи',
              num: '2-9'
            },
            {
              text: 'Комнат',
              num: '4'
            },
            {
              text: 'Площадь',
              num: '117,47'
            },{
              text: 'Кухня',
              num: '18,16'
            },
          ],
          img: 'plan4.png'
        }
    ],
    
    pagination_layouts: ['1-комнатные', '2-х комнатные', '3-х комнатные', '4-х комнатные'],

    gallery: ['gallery1.png', 'gallery2.png', 'gallery3.png', 'gallery4.png', 'gallery1.png', 'gallery2.png', 'gallery3.png', 'gallery4.png'],

    pagination_progress: ['Декабрь 2021', 'Январь 2022', 'Март 2022', 'Апрель 2022'],

    progress: [
      ['progress1.1.jpg', 'progress1.2.jpg', 'progress1.3.jpg', 'progress1.1.jpg', 'progress1.2.jpg', 'progress1.3.jpg'],
      ['progress2.1.jpg', 'progress2.2.jpg', 'progress2.3.jpg', 'progress2.4.jpg', 'progress2.1.jpg', 'progress2.2.jpg', 'progress2.3.jpg', 'progress2.4.jpg'],
      ['progress1.1.jpg', 'progress1.2.jpg', 'progress1.3.jpg'],
      ['progress2.1.jpg', 'progress2.2.jpg', 'progress2.3.jpg', 'progress2.4.jpg', 'progress2.1.jpg', 'progress2.2.jpg', 'progress2.3.jpg', 'progress2.4.jpg']
    ],

    news: [
      {
        img: 'new1.jpg',
        text: 'Строительство ЖК «Grand Victoria» выходит на финишную прямую',
        date: '25 января 2022'
      },
      {
        img: 'new1.jpg',
        text: 'Строительство ЖК «Grand Victoria» выходит на финишную прямую',
        date: '25 января 2022'
      },
      {
        img: 'new1.jpg',
        text: 'Строительство ЖК «Grand Victoria» выходит на финишную прямую',
        date: '25 января 2022'
      },
      {
        img: 'new1.jpg',
        text: 'Строительство ЖК «Grand Victoria» выходит на финишную прямую',
        date: '25 января 2022'
      },
    ]
  }),
  methods: {
    initInfraSwiper(pag) {
      this.swiper = new Swiper('.infraSwiper', {
        autoHeight: true,
        spaceBetween: 30,
        modules:[Navigation, Pagination],
        // Optional parameters
        direction: 'horizontal',
        loop: true,

        //If we need pagination
        pagination: {
          el: ".swiper-pagination",
          clickable: true,
          renderBullet: function (index, className) {
            return '<div class="' + className + '">' + pag[index] + "</div>";
          },
        },
      })
    },

    initLayoutsSwiper(pag) {
      this.swiper = new Swiper('.layoutsSwiper', {
        spaceBetween: 30,
        modules:[Navigation, Pagination],
        // Optional parameters
        direction: 'horizontal',
        loop: true,

        //If we need pagination
        pagination: {
          el: ".swiper-pagination",
          clickable: true,
          renderBullet: function (index, className) {
            return '<div class="' + className + '">' + pag[index] + "</div>";
          },
        },
        navigation: {
          nextEl: ".swiper-button-next",
          prevEl: ".swiper-button-prev",
        },
      })
    },

  
    initGallerySwiper() {
      this.swiper = new Swiper(".gallerySwiper", {
        spaceBetween: 10,
        slidesPerView: 2.2,
        centeredSlides: true,
        direction: 'horizontal',
        loop: true,
        modules:[Navigation, Pagination],
        
        pagination: {
          el: ".swiper-pagination",
          type: "progressbar",
        },
        navigation: {
          nextEl: ".swiper-button-next",
          prevEl: ".swiper-button-prev",
        },
      });
    },

    initProgressSwiper(pag) {
      this.swiper = new Swiper('.progressSwiper', {
        effect: "fade",
        modules:[Pagination],
        
        pagination: {
          el: ".swiper-pagination",
          clickable: true,
          renderBullet: function (index, className) {
            return '<div class="' + className + '">' + pag[index] + "</div>";
          },
        },
      })
    },

    initProgressSubSwiper() {
      this.swiper = new Swiper('.progress__subSwiper', {
        spaceBetween: 10,
        slidesPerView: 3,
        modules:[Pagination, Navigation],
        direction: 'horizontal',
        loop: true,

        pagination: {
          el: ".swiper-pagination",
          type: "progressbar",
        },
        navigation: {
          nextEl: ".swiper-button-next",
          prevEl: ".swiper-button-prev",
        },
      })
    },
  },
  mounted() {
    this.initInfraSwiper(this.pagination_infra);
    this.initLayoutsSwiper(this.pagination_layouts);
    this.initGallerySwiper();
    this.initProgressSwiper(this.pagination_progress);
    this.initProgressSubSwiper()
  }    
}
</script>

<style lang="scss">

@import '@/font/BebasNeue/stylesheet.css';
@import '@/font/Montserrat/stylesheet.css';

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
  font-family: 'Montserrat', sans-serif;
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
      font-family: 'Bebas Neue', sans-serif;
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
      background-color: #5B5B5B;
    }
    section:nth-child(odd) {
      .sec-marker {
        background-color: #E31E24
      }
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
        z-index: 0;
      }


      .home__backlight {
        position: absolute;
        z-index: 8;
        transition: all .3s ease;
        opacity: 0;
        cursor: pointer;

        &:hover {
          opacity: 1;
        }

        img {
          width: 100%;
          height: auto;
        }
      }

      .backlight-top {
        top: 1%;
        right: 36%;
        width: 31.7%;
      }
      .backlight-left {
        top: 11.5%;
        left: 1.5%;
        width: 43.7%;
      }
      .backlight-bottom {
        bottom: 1%;
        left: 31.4%;
        width: 55.4%;
      }
      .backlight-right {
        top: 9.5%;
        right: 0.7%;
        width: 38.6%;
      }

      .home__logo {
        position: absolute;
        z-index: 9;
        animation-name: jump_logo;
        animation-timing-function: linear;
        animation-duration: 1s;
        animation-iteration-count: infinite;
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
      
      @keyframes  jump_logo {
        0% {
          transform: translateY(0%);
        }
        50% {
          transform: translateY(21%);
        }
        80% {
          transform: translateY(36%);
        }
        90% {
          transform: translateY(18%);
        }
        100% {
          transform: translateY(0%);
        }
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
        
        &:hover {
          &:before {
            transform: translateX(20px);
          }  
        } 

        &::before {
          position: absolute;
          content: url(@/assets/right.svg);
          transition: all .3s ease;
          top: 20px;
          right: 43px;
        }
      }
    }
    .about {
      position: relative;
      margin-bottom: 96px;

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

      .infraBlock {
        margin: 36px 92px 56px 63px;

        .swiper-pagination-bullets {
          display: flex;
          justify-content: start;
          margin-bottom: 40px;

          .swiper-pagination-bullet {
            margin-right: 40px;
            padding-bottom: 16px;
            cursor: pointer;
          }
          .swiper-pagination-bullet-active {
            border-bottom: 2px solid #E31E24;
            font-weight: 700;
          }
        }
        
        .swiper-wrapper {
          width: 1000px;
        

          .infra__content__item {
            display: flex;
            flex-direction: column;
            min-height: 530px;
            justify-content: space-between;

            .content__text {
              margin-right: 104px;
              font-weight: 300;
              font-size: 16px;
              line-height: 20px;
              margin-bottom: 43px;
              margin-right: 100px;
            }
            
            .illustration {
              margin-bottom: 40px;
              img {
                width: 100%;
              }
            }
            .illustrationList__location {
              display: flex;
              flex-flow: row wrap;
              width: 100%;
              justify-content: space-between;
              max-width: 1225px;
              margin: auto;

              .location__item {
                width: 267px;
                height: 263px;
                margin-right: 40px;
                margin-bottom: 43px;

                &:nth-child(even) {
                  .item__text {
                    background-color: #5B5B5B;
                  }
                }

                .item__img {
                  width: 100%;
                  height: 209px;

                  img {
                    height: 100%;
                    width: 100%;
                  }
                }

                .item__text {
                  position: relative;
                  font-weight: 400;
                  font-size: 14px;
                  line-height: 17px;
                  padding: 10px 10px 10px 20px;
                  color: #FFFFFF;
                  background-color: #E31E24;

                  &::before {
                    position: absolute;
                    content: '';
                    background-color: #fff;
                    width: 1px;
                    height: 31px;
                    top: 13px;
                    left: 10px;
                  }
                }
              }
            }
          }  
        }
      }
    }

    .cond {
      position: relative;

      .condList {
        margin: 36px 92px 96px 63px;
        display: flex;
        justify-content: space-between;

        .cond__item {
          width: 320px;
          height: 120px;
          background-color: #fff;
          border: 0.5px solid #000000;
          display: flex;
          justify-content: start;
          align-items: center;
          padding-left: 20px;
          cursor: pointer;


          &:hover {
            background-color: #E31E24;
            border: 0.5px solid #FFFFFF;
            color: #fff;

            .item__content{
              .item__content__text {
                 color:#fff;
              }
            }

            &:nth-child(odd)  {
              svg {
                path {
                  fill: white;
                }
              }
            }
            &:nth-child(even)  {
              svg {
                path {
                  stroke: white;
                }
              }
            }
          }

          .item__content {
            margin-left: 22px;

            .item__content__text {
              font-weight: 700;
              font-size: 20px;
              line-height: 24px;
              color: #E31E24;
            }
            .item__content__subtext {
              font-weight: 400;
              font-size: 18px;
              line-height: 22px;
              padding-top: 10px;
            }
          }
        }
      }
    }

    .vid {
      position: relative;
      
      .vidBlock {
        margin: 36px 92px 96px 63px;

        .videoPlayer {
          width: 100%;
          height: 60vh;
          margin-bottom: 36px;

          iframe {
            width: 100%;
            height: 100%;
          }
        }
        .viewButtons {
          display: flex;
          justify-content: space-between;
          max-width: 650px;
          margin: auto;

          .view__btn {
            padding: 14px 102px;
            background-color: #fff;
            border: 1px solid #000000;
            font-weight: 600;
            font-size: 16px;
            line-height: 20px;
            cursor: pointer;
          }
        }
      }
    }
    
    .layouts {
      position: relative;

      .layouts__title {
        align-items: center;
      }
      .layoutsBlock {
        margin: 36px 92px 96px 63px;

        .swiper-pagination-bullets {
          display: flex;
          justify-content: center;

          .swiper-pagination-bullet {
            margin-right: 40px;
            padding-bottom: 16px;
            cursor: pointer;
          }
          .swiper-pagination-bullet-active {
            font-weight: 700;
            border-bottom: 2px solid #E31E24;
          }
        }
      
        .swiper-wrapper {
          margin-top: 40px;
          
          .layouts__container__plan {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 27px;

            .planContent {
              display: flex;
              flex-direction: column;

              .plan__title {
                font-weight: 500;
                font-size: 20px;
                line-height: 24px;
                text-transform: uppercase;
                margin-bottom: 34px;
              }

              .plan__list {
                margin-bottom: 42px;

                .plan__item {
                  display: flex;
                  justify-content: space-between;
                  padding-top: 15px;
                  padding-bottom: 15px;
                  width: 279px;
                  font-weight: 400;
                  font-size: 16px;
                  line-height: 20px;
                  
                  .plan__item__num {
                    font-weight: 500;
                  }
                  
                  &:not(:last-child) {
                    border-bottom: 1px solid #000;
                  }
                }
              }
              
              .plan__btn {
                padding: 10px 35px;
                background-color: #E31E24;
                border: 0;
                font-weight: 600;
                font-size: 16px;
                line-height: 20px;
                color: #FFFFFF;
                cursor: pointer;
              }
            }
            
            .plan__img {
              height: 442px;
              width: auto;
              
              img {
                height: 100%;
                width: auto;
              }
            }
          } 
        }

        .plan__navigation {
          display: flex;
          justify-content: space-between;
          width: 88px;
          margin: auto;

          .navigation__vector {
            cursor: pointer;
          }
        }
      }
    }

    .gallery {
      position: relative; 

      .galleryBlock {
        margin-top: 80px;
        width: 100%;
        margin-bottom: 111px;

        .gallerySwiper {
          width: 100%;

          .swiper-wrapper {
            width: 100%;
            margin-bottom: 42px;
            
            .swiper-slide {
              display: flex;
              justify-content: center;
              align-items: center;
              margin-right: 10px;

              .gallery__img {

                img {
                  height: auto;
                  width: 100%;
                }
              }
            }
          }
          

          .gallery__navigation {
            margin-left: 71px;
            display: flex;
            justify-content: space-between;
            width: 88px;

            .navigation__vector {
              cursor: pointer;
            }
          }
          .swiper-pagination {
            width: 77%;
            height: 2px;
            background: rgba(0,0,0,.25);
            position: absolute;
            bottom: 11px;
            top: unset;
            right: 88px;
            left: unset;

            .swiper-pagination-progressbar-fill {
              background-color: #e31e24;
              height: 100%;
              width: 100%;
              position: absolute;
              transform-origin: left;
            }
          }
        }
      }
    }

    .progress {
      position: relative;

      .progressBlock {
        margin: 36px 92px 96px 63px;

        .progressSwiper {
          
          .swiper-pagination-bullets {
            display: flex;

            .swiper-pagination-bullet {
              margin-right: 40px;
              padding-bottom: 16px;
              cursor: pointer;
            }
            .swiper-pagination-bullet-active {
              font-weight: 700;
              border-bottom: 2px solid #E31E24;
            }
          }

          .wrapper__block {
            margin-top: 61px;

            .slide__block {

              .progress__subSwiper {
                
                .subWrapper {
                  .subSlide {
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    margin-right: 10px;

                    .item__img {

                      img {
                        height: auto;
                        width: 100%;
                      }
                    }
                  }
                }
                
                .subSlide__modules {
                  margin-top: 37px;

                  .progress__navigation {
                    display: flex;
                    justify-content: space-between;
                    width: 88px;

                    .navigation__vector {
                      cursor: pointer;
                    }
                  }
                  .subPagination {
                    width: 88%;
                    height: 2px;
                    background: rgba(0,0,0,.25);
                    position: absolute;
                    bottom: 11px;
                    top: unset;
                    right: 0;
                    left: unset;

                    .swiper-pagination-progressbar-fill {
                      background-color: #e31e24;
                      height: 100%;
                      width: 100%;
                      position: absolute;
                      transform-origin: left;
                    }
                  }
                }
              }
            }
          }
        }
      } 
    }

    .news {
      position: relative;

      .newsBlock {
        margin: 36px 92px 121px 63px;

        .news__list {
          display: flex;
          justify-content: space-between;
          width: 100%;

          .new__item {
            width: 244px;
            border: 0.5px solid #E5E5E5;
            position: relative;

            &:not(:last-child) {
              margin-right: 16px;
            }

            &:nth-child(even)  {  
              .new__img {
                .new__date {
                  background-color: #A6A6A6;
                }
              }
            }

            .new__img {
              position: relative;
              display: flex;
              
              img {
                width: 100%;
              }
              .new__date {
                position: absolute;
                right: 0;
                bottom: 0;
                padding: 5px;
                background-color: #E31E24;
                color: #fff;
                font-weight: 300;
                font-size: 14px;
                line-height: 17px;
              }
            }

            .new__text {
              padding: 15px 7px 33px 7px;
              font-weight: 500;
              font-size: 18px;
              line-height: 22px;
            }
          }
        }

        .news__additions {
          margin-top: 12px;
          font-weight: 300;
          font-size: 16px;
          line-height: 20px;
          text-decoration-line: underline;
        }
      }
    }
    
    .consulta { 
      margin: 0 195px 96px 63px;

      .consultaBlock {
        border: 1px solid #A6A6A6;
        position: relative;
        padding-left: 25px;
        padding-right: 17px;

        .consulta__title {
          position: absolute;
          top: -25px;
          left: 13px;
          background-color: #fff;
          padding: 10px 16px;
          font-family: 'Bebas Neue', sans-serif;
          font-style: normal;
          font-weight: 400;
          font-size: 30px;
          line-height: 30px;
          text-transform: uppercase;
        }

        .consulta__data {
          margin-top: 52px;
          display: flex;
          gap: 12px;
          justify-content: space-between;
          align-items: end;
          font-weight: 300;
          font-size: 18px;
          line-height: 22px;

          .consulta__form {
            width: 284px;

            input {
              width: 100%;
              margin-top: 5px;
              border: 1px solid #A6A6A6;
              border-radius: 2px;
              padding: 13px 0 13px 10px;
              font-weight: 300;
              font-size: 18px;
              line-height: 22px;
            }

          }

          .data__send {
            padding: 14px 38px;
            background-color: #E31E24;
            border: 0;
            cursor: pointer;
            font-weight: 600;
            font-size: 16px;
            line-height: 20px;
            color: #FFFFFF;
          }
        }

        .consulta__subtext {
          font-weight: 300;
          font-size: 12px;
          line-height: 15px; 
          margin-top: 14px;
          margin-bottom: 13px;
        }
      }
    }

    .map {
      position: relative;

      .mapBlock {
        width: 100%;
        height: 566px;

        iframe {
          width: 100%;
          height: 100%;
        }
      }
      .map__contacts {
        position: absolute;
        top: 74px;
        right: 218px;
        z-index: 10;
        width: 344px;
        background: #FFF;
        box-shadow: 0px 1px 4px rgba(0, 0, 0, 0.25);
        padding: 20px;

        .contacts__title {
          margin-bottom: 13px;
        }

        .contacts__item {
          display: flex;
          align-items: flex-start;

          .contacts__item-text {
            padding-left: 9px;
            font-weight: 300;
            font-size: 14px;
            line-height: 17px;
          }
        }
        .geo-item {
          margin-bottom: 13px;
        }
      }
    }
  }

  .footer {
    margin-top: 22px;
    margin-bottom: 18px;

    .footerBlock {
      padding-left: 64px;
      padding-right: 584px;

      .footer__copy {
        font-weight: 400;
        font-size: 12px;
        line-height: 14px;
        color: #333333;
      }
      
      .footer__info {
        margin-top: 11px;
        font-family: 'Roboto', sans-serif;
        font-style: normal;
        font-weight: 300;
        font-size: 10px;
        line-height: 12px;
        color: #333333;

      }
    }
  }
}
</style>
