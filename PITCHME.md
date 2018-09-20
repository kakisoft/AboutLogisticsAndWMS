### マークダウンで簡単にスライドが作れるサービス『GitPitch』
### （応用編）
　  

　  
　  
　　　　id:kakisoft
---
作成中
---
### 自己紹介

<br>
<div class="left">
![alt](assets/image/kakisoft01.png)
</div>
<div class="right">
  <table style="white-space: nowrap;border-style: none;">
    <tr>
      <td>@size[0.8em](**名前**)</td>
      <td>
        <ruby>
        <rb>@size[0.8em](垣花　暁)</rb>
        <rp>（</rp>
        <rt>かきのはな　さとる</rt>
        <rp>）</rp>
        </ruby>      
      </td>
    </tr>
    <tr>
      <td>@size[0.8em](**出身**)</td>
      <td>沖縄県</td>
    </tr>
    <tr>
      <td>@size[0.8em](**仕事**)</td>
      <td>物流系エンジニア @size[0.8em](（フリーランス）)</td>
    </tr>
    <tr>
      <td>@size[0.8em](**使う**)</td>
      <td>.NET/Java/PHP/RDB全般</td>
    </tr>
    <tr>
      <td>&nbsp;</td>
      <td>物流業界向けの言語や機器</td>
    </tr>
    <tr>
      <td>@size[0.8em](**趣味**)</td>
      <td>リアル脱出ゲーム</td>
    </tr>
  </table>
</div>
---
---
---
---
## 物流６大機能

 * 輸配送
 * 保管
 * 包装
 * 荷役
 * 流通加工
 * 情報処理
---
---
---
---
### フォントサイズ
---
@size[2.5em](こんな感じ)に、  
フォントのサイズを  
自由に変更できるようになりました。
---
@size[2.0em](@color[blue](こんな感じ))に、  

フォントカラーを @color[#DC143C](自由に設定できる)  
ようになりました。
---
@fa[check-square icon-size1](こんな風に)  
---
@quote[こんな感じで、引用符を<br>記述できます。]
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
---
おわり

