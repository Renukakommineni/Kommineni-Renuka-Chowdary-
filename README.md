def handleKill(signum, frame):
    print("Killing Thread."
    ForceTerminate.FORCE_TERMINATE = True 
    print(threading.active_count())
    exit(0)
if_name_ =="_main_":
os.environ.setdefault("DJANGO_SETTINGS_MODULE","mysite.settings")
from django.core.management import execute_from_command_line
signal.signal(signal.SIGINT,handleKill)
signal.signal(signal.SIGTERM,handleKill)
execute_from_command_line(sys.argv)
