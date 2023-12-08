1. 경고/주의/알림 태그(Hints)

{% hint style="info" %}
**Info hints** are great for showing general information, or providing tips and tricks.
{% endhint %}

{% hint style="success" %}
**Success hints** are good for showing positive actions or achievements.
{% endhint %}

{% hint style="warning" %}
**Warning hints** are good for showing important information or non-critical warnings.
{% endhint %}

{% hint style="danger" %}
**Danger hints** are good for highlighting destructive actions or raising attention to critical information.
{% endhint %}

{% hint style="info" %}

### This is a heading

This is a line

This is an inline <img src=".gitbook/assets/notification.png" alt="" data-size="line"> image

This is a second <mark style="color:orange;background-color:purple;">line</mark>
{% endhint %}

2. 코드 블록

{% code title="index.js" overflow="wrap" lineNumbers="true" %}

```javascript
‌import * as React from 'react';
import ReactDOM from 'react-dom';
import App from './App';

ReactDOM.render(<App />, window.document.getElementById('root'));
```{% endcode %}


3. 임베디드 URL

{% embed url="[URL_HERE](https://www.youtube.com/watch?v=D_uLM5i0Z4c)" %}

4. 탭(여러 개의 언어 코드를 지원할 때 등에 사용 가능)

{% tabs %}

{% tab title="Windows" %} Here are the instructions for Windows {% endtab %}

{% tab title="OSX" %} Here are the instructions for macOS {% endtab %}

{% tab title="Linux" %} Here are the instructions for Linux {% endtab %}

{% endtabs %}


5. API 메서드 블록

{% swagger method="get" path="" baseUrl="" summary="" %}
{% swagger-description %}

{% endswagger-description %}
{% endswagger %}


6. 페이지 링크

{% content-ref url="./" %} . {% endcontent-ref %}
