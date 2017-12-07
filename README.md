# Nightwatch101
手牽手一起來學 Nightwatch！

![Nightwatch.js](https://cythilya.github.io/assets/nightwatch101/nightwatch.png)

## 安裝
安裝步驟如下。

### Step 1：安裝 Nightwatch
安裝最新版的 Nightwatch。

```
npm install [-g] nightwatch
```

### Step 2：安裝 Java Development Kit（JDK）
安裝 [Java Development Kit（JDK）](http://www.oracle.com/technetwork/java/javase/downloads/jdk9-downloads-3848520.html)，至少版本 7 以上。

### Step 3：下載專案
下載本專案並移動到此資料夾底下。

```
git clone https://github.com/cythilya/nightwatch101.git & cd nightwatch101
```

### Step 4：安裝相關檔案
```
npm install
```

### Step 5：啟動 Nightwatch，並進行測試
方法 1：在 package.json 設定的 `npm test` 會執行 Nightwatch 並指定環境為 local 以進行測試。

```
npm test
```

方法 2：使用 Nightwatch Test Runner 進行測試。

```
nightwatch
```

## 測試報告
安裝 [nightwatch-html-reporter](nightwatch-html-reporter)。

```
npm install nightwatch-html-reporter -g
```

執行指令如下，跑一次測試程式，解析 Nightwatch 所產生的 XML 檔案，最後產生客製化測試報告。

```
nightwatch test/e2e/
nightwatch-html-reporter -d ./reports
```

## 教學
待 2018 鐵人賽補好補滿。
