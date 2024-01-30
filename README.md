## 'hover effect-02'

<br>

### • 배포 주소: [https://hover-effect-02.netlify.app/](https://hover-effect-02.netlify.app/)

<br>

#### - 작업 기간: 2021.06

#### - 리팩토링: 2024.01

<br>

### 기술 스택

Development

<p>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white" />
</p>

Config

<p>
<img src="https://img.shields.io/badge/npm-CB3837?style=flat&logo=npm&logoColor=white"/></a>
</p>

Environment

<p>
<img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat&logo=Visual Studio Code&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=Git&logoColor=white"/></a>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></a>
</p>
<br>

### 전체 페이지

<img src="https://github.com/azure0929/hover-effect-02/assets/128226527/d363b30f-205d-43c6-b33d-8e847fdfd943" />

<br><br>

### 💻 주요 기능

---

- flex, @keyframe zoominout

```html
<div class="frame">
  <div class="front">
    <div>
      <img src="images/image-01.png" alt="img1" />
    </div>
    <h2>Seoul</h2>
  </div>
  <div class="back">
    <p>
      대한민국의 수도이자 최대 도시이다. 백제의 첫 수도인 위례성이었고, 고려의
      남경이었으며, 조선의 수도가 된 이후로 현재까지 대한민국
      정치·경제·사회·문화의 중심지이다. 중앙으로 한강이 흐른다.
    </p>
    <a href="#none">Read More</a>
  </div>
</div>
```

```css
.frame:hover .front {
  top: -50%;
  opacity: 1;
  border-radius: 5px 5px 0 0;
  background-color: yellowgreen;
}
.frame:hover .back {
  top: 50%;
  background-color: #fff;
  opacity: 1;
}

@keyframes zoominout {
  0% {
    transform: scale(0.6);
  }
  50% {
    transform: scale(0.8);
  }
  100% {
    transform: scale(0.6);
  }
}
```
