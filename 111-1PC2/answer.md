# 第2次練習-練習-PC2
>
>學號：108111121 
><br />
>姓名：郭柏葳 
><br />
>作業撰寫時間：20 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2022/9/27
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x]說明內容
- [x]個人認為完成作業須具備觀念

## 說明程式與內容

將溫度計讀入值放入該整數變數中，設參數i_In為華氏，d_Ou為浮點數，在使用公式讓溫度轉換


```csharp
  public partial class test : System.Web.UI.Page
    {
        protected void Page_Load(object sender, EventArgs e)
        {
            int i_In = 66377;
            double d_Ou = -999;
            double d_Tmp = (double)i_In;
            d_Ou = (d_Tmp * 9 / 5) + 32;
            Response.Write(d_Ou);
        }
    }
```

若要於內文中標示部分.aspx檔，則使用以下標籤` ```html 程式碼 ``` `，
下段程式碼則為使用後結果：

```html
<%@ Page Language="C#" AutoEventWireup="true" ...>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" ...>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
        </div>
    </form>
</body>
</html>
```


## 個人認為完成作業須具備觀念

需要最基礎的程式語言能力，還有最基礎的閱讀題目的國文能力，需要清晰的邏輯架構以及上課認真聽講才能完成作業
需要知道溫度轉換的公式

