<template>
  <div>
    <nav class="navbar navbar-expand-lg bg-body-tertiary mb-2">
      <div class="container-fluid">
        <a class="navbar-brand" href="/">王氏家族相冊</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                追憶父母
              </a>
              <ul class="dropdown-menu">
                <li>
                  <a class="dropdown-item" href="/parents/inheritance"
                    >家族傳承</a
                  >
                </li>
                <li><a class="dropdown-item" href="#">追憶父親</a></li>
                <li><a class="dropdown-item" href="#">追憶母親</a></li>
                <li><a class="dropdown-item" href="#">想念舅舅</a></li>
              </ul>
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                生活回顧
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">眷村生活</a></li>
                <li><a class="dropdown-item" href="#">軍旅生活</a></li>
                <li><a class="dropdown-item" href="#">團圓相聚</a></li>
                <li><a class="dropdown-item" href="#">重要里程</a></li>
                <li><a class="dropdown-item" href="#">尋根之旅</a></li>
              </ul>
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                享受當下
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">1.芳</a></li>
                <li><a class="dropdown-item" href="#">2.龍</a></li>
                <li><a class="dropdown-item" href="/current/rank3">3.鳳</a></li>
                <li><a class="dropdown-item" href="#">4.中</a></li>
                <li><a class="dropdown-item" href="#">5.鼎</a></li>
                <li><a class="dropdown-item" href="#">6.煌</a></li>
              </ul>
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                展望未來
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">台灣</a></li>
                <li><a class="dropdown-item" href="#">加拿大</a></li>
                <li><a class="dropdown-item" href="#">美國</a></li>
              </ul>
            </li>
          </ul>

          <a class="m-auto" aria-current="page" href="#">登入</a>
        </div>
      </div>
    </nav>
  </div>
</template>

<script setup></script>

<style scoped></style>
