install.packages("pheatmap")
library(pheatmap)
# 打开excel，选中并复制要绘图的数据，注意，剪切板中必须是表达矩阵
Exp<-read.delim(file="clipboard",header=T,row.names=1,sep="\t")
pheatmap(Exp)
pheatmap(Exp,scale="row")
pheatmap(Exp,scale="row",cluster_cols=F)
pheatmap(Exp,scale="row",cluster_cols=F,color = colorRampPalette(c("navy", "white", "firebrick3"))(50))
#cluster_cols=F 意为取消列的聚类，cluster_rows=F 取消行的聚类
#参考简书——生信札记https://www.jianshu.com/p/3ff336a74d7a
