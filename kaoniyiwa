import time
import subprocess

def focus_timer():
    work_duration = 25 * 60  # 25 minutes in seconds
    rest_duration = 5 * 60   # 5 minutes in seconds

    print("专注时钟开始！")

    while work_duration > 0:
        mins, secs = divmod(work_duration, 60)
        timeformat = "{:02d}:{:02d}".format(mins, secs)
        print("剩余时间: " + timeformat, end='\r')
        time.sleep(1)
        work_duration -= 1

    print("\n休息时间！")
    
    # 在这里可以添加提醒代码，例如使用subprocess打开一个音频文件或弹出窗口
    # 示例：subprocess.run(["start", "alarm.mp3"], shell=True)

    time.sleep(rest_duration)
    print("\n休息结束，继续工作！")

if __name__ == "__main__":
    focus_timer()
