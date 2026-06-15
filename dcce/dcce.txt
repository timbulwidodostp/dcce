# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Dynamic Common Correlated Effects Estimation Use dcce With (In) R Software
install.packages("dcce")
library("dcce")
# Estimate Dynamic Common Correlated Effects Estimation Use dcce With (In) R Software
dcce = read.csv("https://raw.githubusercontent.com/timbulwidodostp/dcce/main/dcce/dcce.csv",sep = ";")
dcce <- dcce(dcce, unit_index = "unit_index", time_index = "time_index", formula = dcce ~ dcce_1 + dcce_2 + dcce_3, model = "mg", cross_section_vars = NULL)
dcce
# Dynamic Common Correlated Effects Estimation Use dcce With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished