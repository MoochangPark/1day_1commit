def solution(before, after):
    before = list(before)
    after = list(after)
    for i in range(len(before)):
        if before[i] in after:
            after.pop(after.index(before[i]))
        else:
            return 0
    return 1