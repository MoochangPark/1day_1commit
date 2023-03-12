def solution(i, j, k):
    answer = 0
    for n in range(i, j+1, 1):
        숫자 = list(str(n))
        if str(k) in 숫자:
            answer += 숫자.count(str(k))
        
    return answer