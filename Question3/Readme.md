# Readme

Q3文件中的前三段代码会生成四个列表

p1_data、p2_data、p1_sample、p2_sample

可以直接在jupyter运行，也可以三段全部复制到本地运行



p1_data是一个嵌套列表，每一个一级列表包括着这个球的所有特征

每个二级列表中每一项的含义如下所示，后面的数字代表是第几项

- point_number = 0
- p1_sets_to_win = 1
- p1_games_to_win = 2
- first_serve_success_rate = 3
- point_victor_rate = 4
- p1_ace_sum = 5
- p1_winner_sum = 6
- p1_double_fault_sum = 7
- p1_unf_err_sum = 8
- p1_net_pt_won_rate = 9
- p1_break_pt_won_rate = 10
- p1_rally_distance_avg = 11
- speed_mph_avg =12
- serve_depth_avg = 13
- return_depth_avg = 14
- serve_width_avg = 15
- p1_winner_type_rate = 16



p1_sample 是我们在预测时要用的标签，在非最后一球的情况下是用下一球的胜负作为标签，如果是最后一球则是整场比赛的胜负



p2data和p2sample结构和p1一模一样

