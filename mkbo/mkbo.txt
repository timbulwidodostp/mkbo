# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Estimate the mKBO (multi-group Kitagawa-Blinder-Oaxaca) decomposition Use mkbo (mKBO) With (In) R Software
install.packages("mKBO")
library("mKBO")
# Estimate the mKBO (multi-group Kitagawa-Blinder-Oaxaca) decomposition Use mkbo (mKBO) With (In) R Software
mkbo = read.csv("https://raw.githubusercontent.com/timbulwidodostp/mkbo/main/mkbo/mkbo.csv", sep = ";")
mkbo <- mkbo("PERNP ~ BACHELOR", group = "RACE", data = mkbo)
mkbo
# Estimate the mKBO (multi-group Kitagawa-Blinder-Oaxaca) decomposition Use mkbo (mKBO) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished