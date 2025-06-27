# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Produce traffic-light plots of risk-of-bias assessments Use trafficlight_rob (robvis) With (In) R Software
install.packages("robvis")
install.packages("ggplot2")
library("robvis")
library("ggplot2")
trafficlight_rob = read.csv("https://raw.githubusercontent.com/timbulwidodostp/trafficlight_rob/main/trafficlight_rob/trafficlight_rob.csv",sep = ";")
# Estimation Produce traffic-light plots of risk-of-bias assessments Use trafficlight_rob (robvis) With (In) R Software
trafficlight_rob <- rob_traffic_light(data = trafficlight_rob, tool = "ROB2", psize = 10)
trafficlight_rob
# Produce traffic-light plots of risk-of-bias assessments Use trafficlight_rob (robvis) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished