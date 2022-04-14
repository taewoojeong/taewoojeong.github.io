---
layout: single
title: "[C++]기본 자료형의 종류와 데이터의 표현범위"

categories:
  - LANGUAGECPP

tags:
  - 백준
  - C++

author_profile: true # 왼쪽부분 프로필을 띄울건지

header:
  overlay_image: /assets/images/banner.png
  overlay_filter: 0.5 # 투명도

sidebar:
  title: Posts
  nav: "sidebar-contents"
---

# 기본 자료형의 종류와 데이터의 표현범위

<table style="text-align: center; font-size: 16px;">
  <colgroup>
  <col width="6.25%"/>
  <col width="28.75%" />
  <col width="10%" />
  <col width="65%" />
  </colgroup>
  <thead>
    <tr height="60px">
      <th colspan="2" >자료형</th>
      <th>크기</th>
      <th>값의 표현범위</th>
      <th></th>
    </tr>
  </thead>  
  <tbody>
    <tr height="60px">
      <td rowspan="10" >정수형</td>
      <td>char</td>
      <td rowspan="2">1byte</td>
      <td>-128 ~ 127(-2<sup>7</sup> ~ 2<sup>7</sup> - 1)</td>
    </tr>
    <tr height="60px">
      <td>unsigned char</td>
      <td>0 ~ 255(0 ~ 2<sup>8</sup> - 1)</td>
    </tr>
    <tr height="60px">
      <td>short</td>
      <td rowspan="2">2byte</td>
      <td>-32,768 ~ 32767(-2<sup>15</sup> ~ 2<sup>15</sup> - 1)</td>
    </tr>
    <tr height="60px">
      <td>unsigned short</td>
      <td>0 ~ 65,535(0 ~ 2<sup>16</sup> - 1)</td>
    </tr>
    <tr height="60px">
      <td>int</td>
      <td rowspan="2">4byte</td>
      <td>–2,147,483,648 ~ 2,147,483,647(-2<sup>31</sup> ~ 2<sup>31</sup> - 1)</td>
    </tr>
    <tr height="60px">
      <td>unsigned int</td>
      <td>0 ~ 4,294,967,295(0 ~ 2<sup>32</sup> - 1)</td>
    </tr>
    <tr height="60px">
      <td>long</td>
      <td rowspan="2">4byte</td>
      <td>–2,147,483,648 ~ 2,147,483,647(-2<sup>31</sup> ~ 2<sup>31</sup> - 1)</td>
    </tr>
    <tr height="60px">
      <td>unsigned long</td>
      <td>0 ~ 4,294,967,295(0 ~ 2<sup>32</sup> - 1)</td>
    </tr>
    <tr height="60px">
      <td>long long</td>
      <td rowspan="2">8byte</td>
      <td>–9,223,372,036,854,775,808 ~ 9,223,372,036,854,775,807(-2<sup>63</sup> ~ 2<sup>63</sup> - 1)</td>
    </tr>
    <tr height="60px">
      <td>unsigned long long</td>
      <td>0 ~ 18,446,744,073,709,551,615(0 ~ 2<sup>64</sup> - 1)</td>
    </tr>
    <tr height="60px">
      <td rowspan="3">실수형</td>
      <td>float</td>
      <td>4byte</td>
      <td>&plusmn;3.4 X 10<sup>-37</sup> ~ &plusmn;3.4 X 10<sup>38</sup>(유효자리수 7자리)</td>
    </tr>
    <tr height="60px">
      <td>double</td>
      <td>8byte</td>
      <td>&plusmn;1.7 X 10<sup>-307</sup> ~ &plusmn;1.7 X 10<sup>308</sup>(유효자리수 15자리)</td>
    </tr>
    <tr height="60px">
      <td>long double</td>
      <td>8byte</td>
      <td>&plusmn;1.7 X 10<sup>-307</sup> ~ &plusmn;1.7 X 10<sup>308</sup>(유효자리수 15자리)</td>
    </tr>
  </tbody>
</table>
