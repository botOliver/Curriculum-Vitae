<template>
<div class="main-information__progress">
        <div class="main-information__softs">
          <h3>Навыки:</h3>
          <div class="main-information__personality">
            <div class="main-information-levels">
              <div>Elementary</div>
              <div>Advanced</div>
            </div>
            <div class="main-information__personality-line">
              <div class="main-information__personality-point english"></div>
            </div>
          </div>

          <div class="main-information__personality">
            <div class="main-information-levels">
              <div>Интроверт</div>
              <div>Экстраверт</div>
            </div>
            <div class="main-information__personality-line">
              <div class="main-information__personality-point psychotype"></div>
            </div>
          </div>

          <div class="main-information__personality">
            <div class="main-information-levels">
              <div>Рассеяный</div>
              <div>Организованный</div>
            </div>
            <div class="main-information__personality-line">
              <div class="main-information__personality-point organization"></div>
            </div>
          </div>

          <div class="main-information__personality">
            <div class="main-information-levels">
              <div>Инертный</div>
              <div>Любознательный</div>
            </div>
            <div class="main-information__personality-line">
              <div class="main-information__personality-point educability"></div>
            </div>
          </div>

          <div class="main-information__personality">
            <div class="main-information-levels">
              <div>Нервный</div>
              <div>Стрессоустойчивый</div>
            </div>
            <div class="main-information__personality-line">
              <div class="main-information__personality-point stress"></div>
            </div>
          </div>
        </div>

        <div class="main-information__education">
          <h3>Образование:</h3>
          <div class="main-information__university">
            Высшее: Военно-медицинская академия им. С. М. Кирова. Лечебный факультет 2021г.
          </div>
        </div>
      </div>
</template>

<style lang="scss" scoped>
.main-information__progress {
  max-width: 440px;

    .main-information__softs{
      margin-bottom: 22px;

        .main-information__personality {
          flex-direction: column;
          display: flex;

            &-point {
              position: absolute;
              bottom: -8px;
              width: 16px;
              height: 16px;
              background-color: #7b7b7b;
              border: 2px solid #ffffff;
              border-radius: 50%;

                    &.english {
                      margin-left: 59%;
                        }

                    &.english {
                      margin-left: 59%;
                    }   

                    &.psychotype {
                      margin-left: 65%;
                    }

                    &.organization {
                      margin-left: 76%;
                    }

                    &.educability {
                      margin-left: 70%;
                    }

                    &.stress {
                      margin-left: 80%;
                    }
                  }

                .main-information-levels {
                  display: flex;
                  justify-content: space-between;
                }

                &-line {
                  position: relative;
                  height: 3px;
                  background-color: #d2d2d2;
                  margin: 5px 7px;
                }
            }
        }
    .main-information__education {
        margin-top: 30px;

          h3{
            margin-bottom: 22px;
          }
  }
}
/*
.main-information__softs > h3,
.main-information__education > h3 {
  margin-bottom: 22px;
}

.main-information__progress,
.main-information__softs,
.main-information__personality {
  display: flex;
  flex-direction: column;
}

.main-information__personality {
  gap: 5px;
}

.main-information-levels {
  display: flex;
  justify-content: space-between;
}

.main-information__personality-line {
  position: relative;
  height: 3px;
  background-color: #d2d2d2;
  margin: 5px 7px;
}


.main-information__personality-point {
  position: absolute;
  bottom: -8px;
  width: 16px;
  height: 16px;
  background-color: #7b7b7b;
  border: 2px solid #ffffff;
  border-radius: 50%;
}

.english {
  margin-left: 59%;
}

.psychotype {
  margin-left: 65%;
}

.organization {
  margin-left: 76%;
}

.educability {
  margin-left: 70%;
}

.stress {
  margin-left: 80%;
}

.main-information__education {
  margin-top: 30px;
}*/
</style>
