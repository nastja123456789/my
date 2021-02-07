<template>
  <div class="slide" id="slide2" data-anchor="Аудитории">
    <img src="./20180718_5983.jpg"/>
    <div class="btn-toolbar mb-3" role="toolbar" aria-label="Toolbar with button groups">
						<span class="col-3" id="amount" style="line-height: 38px; font-size: 17pt;">Интервал:
							<span id="lesson-num"></span>
							<span id="lesson-count"></span>
							<span id="lesson-time"></span>
							<span id="lesson-load" style="display: none;"><i class='fa fa-spinner fa-pulse fa-fw'></i></span>
						</span>
      <div class="m-auto col-3">
        <div id="slider-range"></div>
      </div>
      <div class="input-group input-date m-auto">
        <input id="classrooms-datepicker" class="form-control form-control-lg">
      </div>
      <div class="input-group m-auto">
        <div class="btn-group week-changer">
          <button id="prev-day-btn" class="btn btn-outline-secondary btn-lg" type="button" title="Предыдущий день">
            <i class="fa fa-arrow-left"></i>
          </button>
          <button id="next-day-btn" class="btn btn-outline-secondary btn-lg" type="button" title="Следующий день">
            <i class="fa fa-arrow-right"></i>
          </button>
        </div>
      </div>
      <button id="classrooms-clear" class="btn btn-outline-danger clear-filter m-auto btn-lg" type="button">
        <i class="fa fa-times fa-fw"></i>
      </button>
    </div>
    <div class="col-sm-11" id="free-classes-ruz">
      <div id="sleep_menu">
        <div id="sleep_check"></div>
        <div class="info-menu">
          <div class="top-menu shadow">
            <div class="top-left-menu">
              <div id="time"><span id="time-node"></span> <i class="far fa-clock"></i> </div>
            </div>
            <div class="top-menu-content"><h2><i class="mdi mdi-gesture-tap h1"></i> чтобы начать работу</h2></div>
          </div>
          <div class="left-menu shadow">
            <div class="free-class-title">Свободные аудитории на 3 пару (12:10-13:30)</div>
            <ul class="free-classes" id="free-classes-sm">
              <li class="floar">
                <h6>1 ЭТАЖ</h6>
                <p>107 <small>(30)</small>, 121 <small>(16)</small></p>
              </li>
              <li class="floar">
                <h6>2 ЭТАЖ</h6>
                <img src="/src/components/navigation/загрузка%20(2).svg" v-if="show"/>
                <p>208 <small>(50)</small>, 209 <small>(16)</small>, 212 <small>(16)</small>, 213 <small>(27)</small>, 228а <small>(16)</small>, 233а <small>(16)</small></p>
              </li>
              <li class="floar">
                <h6>3 ЭТАЖ</h6>
                <p>302 <small>(32)</small>, 309 <small>(16)</small>, 311 <small>(18)</small>, 313 <small>(28)</small></p>
              </li>
              <li class="floar">
                <h6>4 ЭТАЖ</h6>
                <p>409 <small>(12)</small>, 410 <small>(150)</small>, 411 <small>(16)</small>, 412 <small>(148)</small>, 413 <small>(100)</small>, 414 <small>(14)</small>, 424 <small>(32)</small>, 425 <small>(10)</small>, 427 <small>(12)</small>, 435 <small>(10)</small></p>
              </li>
              <li class="floar">
                <h6>5 ЭТАЖ</h6>
                <p>506 <small>(200)</small>, 512 <small>(12)</small>, 515 <small>(18)</small>, 520 <small>(18)</small>, 522 <small>(20)</small></p>
              </li>
              <li class="floar">
                <h6>6 ЭТАЖ</h6>
                <p>606 <small>(20)</small></p>
              </li>
              <li class="floar">
                <h6>7 ЭТАЖ</h6>
                <p>703 <small>(12)</small></p>
              </li>
              <li class="floar">
                <h6>8 ЭТАЖ</h6>
                <p>802 <small>(30)</small>, 807 <small>(10)</small>, 808 <small>(10)</small></p>
              </li>
              <li class="floar">
                <h6>9 ЭТАЖ</h6>
                <p>904 <small>(0)</small></p>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>


</template>

<script>
export default {
  name: "freeaudit"
}
</script>

<style scoped>

</style>