# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Probit Model with Random Effects Use ProbitRE With (In) R Software
install.packages("PanelCount")
library("PanelCount")
ProbitRE = read.csv("https://raw.githubusercontent.com/timbulwidodostp/ProbitRE/main/ProbitRE/ProbitRE.csv",sep = ";")
# Estimation Probit Model with Random Effects Use ProbitRE With (In) R Software
ProbitRE = ProbitRE(z~x+w, data=ProbitRE, id.name='id', verbose=-1)
ProbitRE$estimates
# Probit Model with Random Effects Use ProbitRE With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished