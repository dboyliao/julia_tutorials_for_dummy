# Julia 超新手教學
Julia tutorials for dummy.

## Installation

### Install Julia

到 [官方下載頁面](https://julialang.org/downloads/) 下載目前穩定版（Current Release）。
請根據你的電腦作業系統以及位元版本下載相對應的安裝檔。

> Windows
> 直接點擊安裝檔 ~~無腦~~ 安裝。

### Test Julia

> Windows
> 左下方"開始" > "搜尋" > 打入"cmd" > 執行"命令提示字元" > 打入"julia"

### Install Jupyter

建議安裝 [Anaconda](https://www.anaconda.com/download/)，請選擇 Python 3.6 的版本安裝。

當中內建 Jupyter 可以直接執行。

### Install IJulia

> Windows
> 左下方"開始" > "搜尋" > 打入"cmd" > 執行"命令提示字元" > 打入"julia"
> 會進入 Julia 的互動式命令介面
> 打入 `Pkg.update()` 做套件更新，請確定你有連上網路
> 打入 `Pkg.add("IJulia")` 安裝 IJulia。
> 安裝成功後，打入 `using IJulia`
> 打入 `notebook()` 開啟 Jupyter

## Usage

###
