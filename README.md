# code_cluase_url_shortener_project
import pyshorteners
url=input("Enter the url:\n")
def shortenurl(url):
    s=pyshorteners.Shortener()
    return s.tinyurl.short(url)
short=shortenurl(url)
print("url after shortening:",short)
