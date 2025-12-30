# Airline_Simulator
A new developing game.

Development Log

2025

[v0.0]

11.27：确定程序整体框架

11.28：创建线程、定时器，优化Decodef函数

11.29：写入Helpf、Timef、Play_timef、To_Radiansf、Haversinef、Confirmf、Route_judgef、Plane_judgef、Cash_flowf、Financef、Fleetf、Routef、Purchasef函数，优化Thread_command_input、Thread_system_input、Thread_finance_input、Thread_notice_input四个线程，优化Decodef、Timef函数，优化基础结构体，优化机场、飞机具体数据

12.6：重架构Decodef函数，优化Routef、Cash_flowf、Play_timef函数，删除Thread_finance_input线程

12.7：写入Route_arrangef、Purchase_introf、Planeinf_iptf、Plane_judgef函数，重架构Decodef、Helpf、Route_judgef函数，优化Purchasef、Routef函数，删除Confirmf函数

12.8：优化航段数据

12.10：优化现金流与票价计算功能

12.11：写入Pricef、Dprnf函数，优化Routef、Cash_flowf、Planeinf_iptf、Financef、Fleetf函数，删除Thread_system_input线程

[v0.1]

12.14：写入define.h头文件，写入Sellf、Leasef、Planeinf_inif函数，重架构Fleetf函数，优化Thread_notice_input线程、优化Decodef、Cash_flowf函数

[v0.2]

12.27：写入Status_judgef、Gametime_judgef函数，重架构Planeinf_iptf、Purchasef、Purchase_introf、Plane_judgef函数，删除Route_judgef、Leasef函数，优化Play_timef函数，优化飞机具体数据

12.28：写入Errorf函数，将Plane_judgef函数更名为Matchf函数，重架构Matchf、Purchasef函数，优化Decodef函数，优化数据结构，优化飞机具体数据

12.30：写入Purchase_updatef函数，重架构Matchf、Purchasef、Purchase_introf函数，优化数据结构
