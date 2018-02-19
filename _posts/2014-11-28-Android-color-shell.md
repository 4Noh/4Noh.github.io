---
layout: post
title: Android color shell
feature-img: "assets/img/sample_feature_img.png"
tags: Android
---

루트 필요

1. busybox 설치(https://play.google.com/store/apps/details?id=stericson.busybox&hl=en)
2. adb shell 열기
3. 환경변수 `PATH` (export PATH=/su/xbin/:$PATH)

`busybox` 명령어의 우선 순위가 높아짐
--> `ls --color` 대신 `ls`만 해도 색이 나옴

