### マークダウンで簡単にスライドが作れるサービス『GitPitch』
### （応用編）
　  

　  
　  
　　　　id:kakisoft
---
作成中
![alt](assets/image/kakisoft01.png)
---
### 自己紹介

<div class="left">
  ![alt](assets/image/kakisoft01.png)
</div>
<div class="center">
    <ul>
        <li> **名前：** 垣花　暁（かきのはな　さとる）</li>
        <li>使えるので、</li>
        <li>レイアウトは</li>
        <li>基本的に</li>
        <li>自由自在です。</li>
    </ul>
</div>
---
### 自己紹介  
　  
**名前**：垣花　暁（かきのはな　さとる）    
　  
**出身**：沖縄県  
　  
**仕事**：物流系エンジニア（フリーランス）  
.NET/Java/PHP/RDB全般。  
物流業界向けの言語や機器が使えます。  
　  
**趣味**：リアル脱出ゲーム
---
このスライドは、**「GitPitch」**という、  
GitHubアカウントがあれば、マークダウンで  
スライドが作成できるサービスを利用しています。
---
よく使っているのですが、  
色々と機能が増えているので、  
もう少し使ってみました。
---
基本的な使い方は、[こちらのスライド](https://gitpitch.com/kakisoft/HowToUseGitPitch)  
にて紹介しています。  
　  
初めて使う方は、上記のスライドを先に、  
ご参照頂けたらと思います。
---
追加機能
---
### フォントサイズ
---
@size[2.5em](こんな感じ)に、  
フォントのサイズを  
自由に変更できるようになりました。
---
書き方は、**『@size\[2.5em\](こんな感じ)』** です。
　  
　  
@size[1.1em](「@size」を記述し、\[フォントサイズ\] (文字))  
と、記述します。
---
### フォントカラー
---
@size[2.0em](@color[blue](こんな感じ))に、  

フォントカラーを @color[#DC143C](自由に設定できる)  
ようになりました。
---
書き方は、**『@color\[blue\](こんな感じ)』** です。
　  
　  
@size[1.1em](「@color」を記述し、\[色\] (文字))  
と、記述します。
---
### カスタムCSS
---
PITCHME.yaml（設定ファイル）にて、  
以下のように、カスタム CSSが設定できます。
```
theme-override : assets/css/PITCHME.css
```

---
例えば、以下のような css を記述し、
```css
.headline {
  color: blue;
  font-size: 1.1em;
}
```
こんな感じに @css[headline](使う事が出来ます。)
---
書き方は、**『@css\[クラス\](内容)』** です。
　  
　  
@size[1.1em](「@css」を記述し、\[クラス\] (文字))  
と、記述します。
---
### アイコン
---
@fa[check-square icon-size1](こんな風に)  
　  
@fa[twitter icon-size2](色々なアイコンが)  
　  
@fa[github icon-size3](使えるようになっていて)  
　  
@fa[bolt fa-2x](大きさも指定できます)  
---
書き方は、**『@fa\[アイコン名 サイズ\](テキスト)』**   
です。    
　  
サイズと文字は省略可能です。  
また、CSSを適用する事もできます。
---
アイコンギャラリーは [こちら](https://fontawesome.com/icons?from=io)。
　  
![alt](assets/image/icon-gallery.png)  

何が使えて、何が使えないか良く分からないので、  
[使えるアイコンをリストアップしました。](https://gitpitch.com/kakisoft/GitPitchIconList#/)
---
### 引用
---
@quote[こんな感じで、引用符を<br>記述できます。]
---
書き方は、**『@quote\[こんな感じ\]』** です。
---
### スライドの遷移
---
現在、スライドの遷移は、  
「transition : convex」という設定です。
---
@transition[zoom-in fade-out]
ですが、一部のスライドだけを
---
@transition[concave]
こうしたり
---
@transition[zoom]
こうしたり
---
@transition[slide]
こんな感じで
---
@transition[fade]
スライドのアニメーションを  
変える事が出来ます。
---
書き方は、**『@transition\[遷移タイプ\]』** です。
　  
遷移タイプは、以下が設定できます。
```
convex, concave, default,
fade, none, slide, zoom
```
---
### 文字の配置
---
@transition[none]

@snap[north]
こんな感じで
@snapend

@snap[west]
自由に
@snapend

@snap[midpoint]
文字を
@snapend

@snap[east]
配置
@snapend

@snap[south]
できます
@snapend
---
書き方は、  
___
@ snap\[ポジション\]<br>@size[0.7em](（内容）)<br>@ snapend  
___
です。  
　  
ポジションは、以下が設定できます。
```
east, west, south, north
midpoint
```
---
### 他にも色々できます

<br>
<div class="left">
    <i class="fa fa-child fa-5x" aria-hidden="true"> </i><br>
    <a href="https://gitpitch.com/docs/about/" class="pro-link">
    詳細はこちら</a>
</div>
<div class="right">
    <ul>
        <li>HTMLのタグが</li>
        <li>使えるので、</li>
        <li>レイアウトは</li>
        <li>基本的に</li>
        <li>自由自在です。</li>
    </ul>
</div>
---
マークダウンとHTMLでスライドが作れるのは、  
手軽で便利だと思ってます。
---
興味が沸いた方は、是非使ってみて下さい！  
https://gitpitch.com/
---
また、このスライドのリポジトリは、  
[こちら](https://github.com/kakisoft/HowToUseGitPitch3)です。
---?image=assets/image/gitpitch-audience.jpg
@size[2.0em](@color[white](おわり))

