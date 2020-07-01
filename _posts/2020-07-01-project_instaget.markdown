---
layout: post
title:  "Project_instaget"
date:   2020-07-01 12:00:00 +0900
categories: Flask
---
2018.10 부터 현재까지 개발 중인 인스타겟입니다.

 - CS 업무 편의기능 및 운영 보조 사이트 개발 (docker, bootstrap)
    - 작업 진행상황 및 상세내역 조회 (pymysql, psycopg2)
    - 인스타그램 게시물 업로드 시간 조회
    - 관리자용 주문 페이지 구현
    
 - 마이페이지 구현
   - 회원정보관리 기능 추가
   
 - 고객 후기 페이지 및 상품 추가
   - 데스크탑 모바일 버전 UI/UX 개선
   - 유튜브 페이스북 상품 추가 (html, js)
    
 - 인스타그램 유저 및 게시물 정보 확인부 구현
   - 인스타그램 API 를 이용한 유저 정보 확인 (asnyc, multiThread)
   - API 가 문제있을 시 데이터 크롤링 후 유저 정보 확인되도록 (selenium, bs4)
   
 - 2017 legacy 코드 리팩토링
   
 - 결제, 상품조회 등 리소스 많이 사용되는 로직 최적화
   - row 가 많은 테이블에서 데이터 가져올 때 페이지네이션 처리 (sqlalchemy_paginate)
   
 - REST API 기능 개발 (ajax)
   - 해외 무통장입금 시스템 구축
   - 어드민 편의 기능 추가
   - 주문 페이지에서 유저 정보 콜백
   - 리뷰 작성 시 구매한 상품이 있는지부터 조회
   
 - 인스타겟 다국어 버전 런칭
   - 인도네시아, 글로벌 버전 개발 (i18n)
   
 - SEO 구성
   - 네이버에서 검색시 노출이 종종 안될 때마다 seo 정보 수정
   
 - 내부 인프라 관리 시스템 개발
   - 프록시 상태 검증 스크립트 작성 (aiohttp)
   - 필요 사진 정보 캐시 (PIL, Imagehash)
   - 서버 health_check 및 sentry 부착 (HealthCheck, sentry-sdk)
   - middle ware 추가하여 prod 환경과 staging 환경 구분 (flask_middleware)
   
 - 기타 유지보수 진행
