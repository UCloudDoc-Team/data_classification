# 为什么添加 SqlServer 时，无法扫描到表和字段 

源数据库执行了字段、表等信息的修改后，请在源数据库列表页面执行更新操作。

注意：1，源数据库处于审核通过的状态、进行修改后审核状态将会变为未审核的状态，并且源数据库信息已应用于未运行的任务中，则该任务状态转换为未审核。2，若修改了源数据信息，并且源数据库信息已应用于正在运行的任务中，则会停止任务，任务状态转换为未审核状态。