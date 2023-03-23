# Observer-Example
觀察者模式範例紀錄

## 實做大至分類:
* 主體類別
``` C#
Subject { 
    
    Observer觀察者List

    註冊方法

    取消註冊方法

    通知方法<執行Observer的更新方法> 
}
```


* 某某主題類別
``` C#
Subject實例{  //繼承Subject

    override

    其他方法

}
```

* 觀察者類別
``` C#
Observer{

    被通知之後的更新方法

    取得Subject的方法

}
```

* 某某觀察者類別
``` C#
Observer實例{    //繼承Observer

    override<更新方法裡面直接取Subject裡的方法>

    其他方法

}
```
