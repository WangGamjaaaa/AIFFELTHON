# <span style = "font-weight:bold;color:#0172d4;">SIA</span> 프로젝트 소개

<img src = "./img/sia_logo.png" style = "width: 100%;">

<br><br>

## 1. 목표 
<ul style = "font-size:15px;">
    <li style = "margin-bottom:20px;">위성 영상에서 <span style = 'background-color:#fff5b1; padding:0.2px;'>항공기, 선박, 차량의 위치를 식별</span>한다.</li>
</ul>

<br><br>

## 2. Level Step

<ul style = "font-size:15px;">
    <li style = "margin-bottom:20px;">데이터에서 항공기, 선박, 차량으로만 이루어진 데이터셋으로 정제한다. (일반 ★☆☆☆☆)</li>
    <li style = "margin-bottom:20px;">세 가지 Class에 대해 <span style = 'background-color:#fff5b1; padding:0.2px;'>객체 검출을 위한 학습</span>을 수행하고 결과를 표출한다. (클래스 별로 각각의 모델을 만들어도 좋습니다) (어려움 ★★☆☆☆)
</li>
    <li style = "margin-bottom:20px;">Level2의 결과를 평가를 하고 성능 개선하기 (어려움 ★★★★☆)</li>
</ul>

<br><br>

## 3. Data Set:  Fair1M-2.0

### Image

<ul style = "font-size:15px;">
    <li style = "margin-bottom:20px;">Gaofan에서 취득한 위성영상으로, Gaofan(GF)은 인공 위성을 뜻한다.</li>
    <li style = "margin-bottom:20px;">600x600 ~ 9472 x 10000 까지 다양한 크기의 Scene 형태</li>
    <li style = "margin-bottom:20px;">TIF 확장자로 제공</li>
    <li style = "margin-bottom:20px;">GSD(Ground Sample Distance): 0.3m ~ 0.8m</li>
</ul>

### Label

<ul style = "font-size:15px;">
    <li style = "margin-bottom:20px;">객체의 Class, Polygon 등의 정보를 xml 확장자로 제공</li>
    <li style = "margin-bottom:20px;">이미지 파일에 대한 정보가 들어있음</li>
    <li style = "margin-bottom:20px;">filename, origin, width, height, depth, coordinate, type, description, name, point 등으로 이루어짐</li>
</ul>

<br><br>

## 4. 팀원 구성

<table style = "width:100%; margin:auto; border:0.5px solid #c1c1c1; font-size:15px;">
    <th style = "width:20%; padding:10px; text-align:center; border:0.5px solid #c1c1c1;">이름</th>
    <th style = "width:20%; padding:10px; text-align:center; border:0.5px solid #c1c1c1;">구성</th>
    <th style = "width:60%; padding:10px; text-align:center; border:0.5px solid #c1c1c1;">역할</th>
    <tr>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;">김현호</td>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;">팀장</td>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;">파이토치, WanDB, base model 구축, 데이터 재구성, 모델링 및 Loss Function 비교 분석</td>
    </tr>
        <tr>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;">박혁성</td>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;">팀원</td>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;">논문 조사, GIS Mapping, GCP 운용, 전체적인 QGIS 툴 전담 역할, 모델링 및 Loss Function 비교 분석</td>
    </tr>
        <tr>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;">윤혜연</td>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;">팀원</td>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;">데이터 EDA 및 시각화, 회의록 작성 및 스케줄 관리, 모델링 및 Loss Function 비교 분석 </td>
    </tr>
</table>

<br><br>

## 5. 프로젝트 진행 

<table style = "width:100%; border:0.5px solid #c1c1c1; font-size:15px;">
    <th style = "width:70%; padding:10px; text-align:center; border:0.5px solid #c1c1c1;">진행 사항</th>
    <th style = "width:30%; padding:10px; text-align:center; border:0.5px solid #c1c1c1;">code link</th>
    <tr>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;">데이터 EDA</td>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;"><a href = "">code</a></td>
    <tr>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;">Base line model</td>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;"><a href = "">code</a></td>
    </tr>
    <tr>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;">model name01</td>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;"><a href = "">code</a></td>
    </tr>
    <tr>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;">model name02</td>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;"><a href = "">code</a></td>
    </tr>
    <tr>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;">model name03</td>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;"><a href = "">code</a></td>
    </tr>
    <tr>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;">model name04</td>
        <td style = "padding:10px; text-align:center; border:0.5px solid #c1c1c1;"><a href = "">code</a></td>
    </tr>
</table>

<br><br>
