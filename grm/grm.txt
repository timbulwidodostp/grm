# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Graded response model - polytomous IRT Use grm (ltm) With (In) R Software
install.packages("ltm")
library("ltm")
grm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/grm/main/grm/grm.csv",sep = ";")
# Estimation Graded response model - polytomous IRT Use grm (ltm) With (In) R Software
grm(grm)
grm(grm[c(1,3,4,7)])
grm(grm[c(1,3,4,7)], constrained = TRUE)
# Graded response model - polytomous IRT Use grm (ltm) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished