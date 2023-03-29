def solution(quiz):
    answer = []
    quiz = [i.split("=") for i in quiz]
    for j in quiz:
        print(j)
        if eval(j[0]) == int(j[1]):
            answer.append("O")
        else:
            answer.append("X")
    return answer