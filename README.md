# develop-test-deploy-azure-functions-with-visual-studio

https://docs.microsoft.com/ja-jp/learn/modules/develop-test-deploy-azure-functions-with-visual-studio/  

## 特記事項

1. Azure Functions v3 でも同様の操作で可能です。  
（ランタイムは .NET Core 3.1 です。）  
2. Visual Studio 2017 で解説されていますが Visual Studio 2019 でも可能です。   
3. テストプロジェクトはテスト対象のプロジェクト参照の手順が無いのでテストプロジェクト作成後に参照してください。    

  3.1 テストプロジェクトの依存関係で右クリック
  ![テストプロジェクトの依存関係](project-ref-01.png)

  3.2 表示されたメニューからプロジェクト参照の追加をクリック。  
  ![テストプロジェクトの依存関係](project-ref-02.png)  

  3.3 テスト対象のプロジェクトのチェックを付けて OK をクリック。  
  ![テストプロジェクトの依存関係](project-ref-03.png)  


