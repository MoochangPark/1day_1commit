def solution(x, n):
    answer = [x + (x * j) for j in range(n)]
    return answer