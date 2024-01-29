<template>
  <div class="login">
    <div class="overlap-wrapper">
      <div class="overlap">
        <div class="group">
          <div class="ellipse" />
        </div>
        <div class="ellipse-wrapper">
          <div class="ellipse" />
        </div>
        <div class="frame">
          <div class="overlap-group">
            <div class="frame-2">
              <div class="frame-3">
                <Placeholder
                  class="placeholder-instance"
                  div-class="placeholder-2"
                  label-div-class="design-component-instance-node"
                  label-text="Username"
                  size="large"
                  state="default"
                  text="Masukkan username"
                  type="placeholder-only"
                />
                <div class="frame-4">
                  <Placeholder
                    class="placeholder-instance"
                    div-class="placeholder-2"
                    label-div-class="design-component-instance-node"
                    label-text="Password"
                    size="large"
                    state="default"
                    text="Masukkan password"
                    type="placeholder-only"
                  />
                  <div class="text-wrapper-2">Lupa password?</div>
                </div>
              </div>
              <Button
                class="button-instance"
                content="label-only"
                div-class="button-2"
                size="large"
                state="initial"
                text="Login"
                type="primary"
              />
            </div>
            <UEye class="u-eye" color="#CCCCCC" />
          </div>
        </div>
        <div class="logo-qursa">
          <img class="vector" alt="Vector" src="vector.svg" />
          <img class="img" alt="Vector" src="image.svg" />
          <img class="vector-2" alt="Vector" src="vector-2.svg" />
        </div>
        <div class="text-wrapper-3">Welcome</div>
      </div>
    </div>
  </div>
</template>

<script>
import { Button } from "./Button";
import { Placeholder } from "./Placeholder";
import { UEye } from "./UEye";

export default {
  name: "Login",
  components: {
    Button,
    Placeholder,
    UEye,
  },
};
</script>

<style>
.login {
  background-color: #a9c4f3;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
}

.login .overlap-wrapper {
  background-color: var(--primary-20);
  height: 1024px;
  overflow: hidden;
  width: 1440px;
}

.login .overlap {
  height: 1672px;
  left: -232px;
  position: relative;
  top: -327px;
  width: 1909px;
}

.login .group {
  background-color: #ffffff1a;
  border-radius: 463px;
  height: 926px;
  left: 0;
  position: absolute;
  top: 746px;
  width: 926px;
}

.login .ellipse {
  background-color: #ffffff1a;
  border-radius: 269px;
  height: 538px;
  left: 194px;
  position: relative;
  top: 194px;
  width: 538px;
}

.login .ellipse-wrapper {
  background-color: #ffffff1a;
  border-radius: 463px;
  height: 926px;
  left: 983px;
  position: absolute;
  top: 0;
  width: 926px;
}

.login .frame {
  background-color: var(--neutral-1);
  border-radius: 20px;
  box-shadow: var(--shadow-2);
  height: 600px;
  left: 660px;
  overflow: hidden;
  position: absolute;
  top: 540px;
  width: 580px;
}

.login .overlap-group {
  height: 305px;
  left: 127px;
  position: relative;
  top: 175px;
  width: 326px;
}

.login .frame-2 {
  align-items: center;
  display: inline-flex;
  flex-direction: column;
  gap: 30px;
  justify-content: center;
  left: 0;
  position: absolute;
  top: 0;
}

.login .frame-3 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 24px;
  position: relative;
}

.login .placeholder-instance {
  flex: 0 0 auto !important;
}

.login .design-component-instance-node {
  font-family: "Inter-SemiBold", Helvetica !important;
  font-size: 14px !important;
  font-style: unset !important;
  font-weight: 600 !important;
  letter-spacing: 0 !important;
  line-height: 16px !important;
}

.login .placeholder-2 {
  font-family: "Inter-Medium", Helvetica !important;
  font-size: 12px !important;
  font-style: unset !important;
  font-weight: 500 !important;
  letter-spacing: 0 !important;
  line-height: 16px !important;
}

.login .frame-4 {
  align-items: flex-end;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 16px;
  position: relative;
}

.login .text-wrapper-2 {
  color: #000000b2;
  font-family: "Inter-Medium", Helvetica;
  font-size: 12px;
  font-weight: 500;
  letter-spacing: 0;
  line-height: 19px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.login .button-instance {
  background-color: #2d64f3 !important;
  flex: 0 0 auto !important;
}

.login .button-2 {
  font-family: "Inter-Bold", Helvetica !important;
  font-size: 18px !important;
  font-style: unset !important;
  font-weight: 700 !important;
  letter-spacing: 0 !important;
  line-height: 30px !important;
  margin-left: -19.5px !important;
  margin-right: -19.5px !important;
}

.login .u-eye {
  height: 24px !important;
  left: 286px !important;
  position: absolute !important;
  top: 151px !important;
  width: 24px !important;
}

.login .logo-qursa {
  height: 50px;
  left: 927px;
  position: absolute;
  top: 579px;
  width: 50px;
}

.login .vector {
  height: 32px;
  left: 8px;
  position: absolute;
  top: 14px;
  width: 34px;
}

.login .img {
  height: 6px;
  left: 17px;
  position: absolute;
  top: 4px;
  width: 6px;
}

.login .vector-2 {
  height: 6px;
  left: 27px;
  position: absolute;
  top: 4px;
  width: 6px;
}

.login .text-wrapper-3 {
  color: var(--neutral-50);
  font-family: "Inter-Bold", Helvetica;
  font-size: 34px;
  font-weight: 700;
  left: 870px;
  letter-spacing: 0;
  line-height: 55px;
  position: absolute;
  text-align: center;
  top: 640px;
  white-space: nowrap;
}
</style>