# Hello_World
# I am a junior business anaylitics and information systems major at university of Iowa. I am mostb comfortable coding with python and sql.
# here is some cool python function I wrote to return words within a string that contain certain characters
def filterWords(S, c1, c2=''):
    def Contains(N):
        return(c1 in N and c2 in N)
    return(list(filter(Contains, S.lower().split())))
