pollutantmean<-function(directory,pollutant,id=1:200){
  a<-list.files(path=directory,pattern=".csv")
  x<-numeric()
  for(i in id){
    b<-read.csv(a[i])
    x<-c(x,b[[pollutant]])
  }
  mean(x,na.rm=T)
}