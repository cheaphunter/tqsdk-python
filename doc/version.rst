.. _version:

版本变更
=============================
2019/01/21:
 * 加入双均线策略
 * 加入网格交易策略
 * 数据下载器支持按交易日下载数据
 * 修正模拟交易数据不正确的问题
 * 修正回测时出现“平仓手数不足"的问题

2018/12/12:
 * 加入直连行情交易服务器模式
 * 模拟交易结束后输出交易报告
 * 修正回测时账户资金计算错误的问题

2018/11/16:
 * 加入策略回测功能

2018/10/25:
 * 加入海龟策略

2018/10/17:
 * 加入 dual thrust 策略
 * 加入 r-breaker 策略

2018/08/30:
 * 目标持仓模型(TargetPosTask)支持上期所的平今平昨和中金所禁止平今
 * K线/Tick序列加入 to_dataframe 函数将数据转为 pandas.DataFrame
 * 加入 close 函数用于退出时清理各种资源
 * wait_update 由设定超时秒数改为设定截止时间, 并返回是否超时
 * 加入调试模式，将调试信息写入指定的文件中
 * 修正和某些开发环境不兼容的问题
 * 规范了各业务数据的类型
 * register_update_notify 支持监控特定的业务数据

2018/08/10:
 * 目标持仓Task自动处理上期所平今/平昨
 * 主力合约加入 underlying_symbol 字段用来获取标的合约
 * 更新文档
