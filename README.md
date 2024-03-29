




```
r language BS26, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis özofagus, SCC radyoterapi sonrası keratin granülomları TR, echo = (language == "TR")
## BS26 - özofagus, SCC radyoterapi sonrası keratin granülomları {#sec-BS26 }
```


```
asis esophagus, keratin granulomas after radiotherapy for SCC EN, echo = (language == "EN")
## BS26 - esophagus, keratin granulomas after radiotherapy for SCC {#sec-BS26 }
```






```
r BS26 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS26-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS26/HE.html",
  file = "./screenshots/BS26-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/BS26/HE.html](https://images.patolojiatlasi.com/BS26/HE.html)





```
asis, echo = (language == "TR")

**özofagus, SCC radyoterapi sonrası keratin granülomları**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS26-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS26/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS26/HE.html)
```

```
asis, echo = (language == "EN")

**esophagus, keratin granulomas after radiotherapy for SCC**

[![Click for Full Screen WSI](./screenshots/BS26-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS26/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS26/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS26/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS26/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

özofagus, SCC radyoterapi sonrası keratin granülomları

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

esophagus, keratin granulomas after radiotherapy for SCC

:::

```









:::::









