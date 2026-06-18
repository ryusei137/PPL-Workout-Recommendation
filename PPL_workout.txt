ppl = input('push, pull, legsの中から一つ選んでください: ')

if ppl == 'push':
    print('今日はベンチプレス、サイドレイズ、トライセプスエクステンションをしてください')

    muscle = input('最初にやる種目を決めてください: ')

    if muscle == 'ベンチプレス':
        print('それは多関節種目です')
    else:
        print('それは単関節種目です')

    month = input('筋肥大の月か筋力の月か選んでください: ')

    if month == '筋肥大の月':
        print('レップ数は8~10回です')
    else:
        print('レップ数は1~5回です')

elif ppl == 'pull':
    print('今日はデッドリフト、EZバーカール、ケーブルリアをしてください')

    muscle = input('多関節種目を選択してください: ')
    print(f'今日の多関節種目は{muscle}です')

    month = input('筋肥大の月か筋力の月か選んでください: ')

    if month == '筋肥大の月':
        print('レップ数は8~10回です')
    else:
        print('レップ数は1~5回です')

elif ppl == 'legs':
    print('今日の種目はスクワット、レッグカール、レッグエクステンションです')

    muscle = input('単関節種目を入力してください: ')
    print(f'legsの日の単関節種目は{muscle}です')

    month = input('筋肥大の月か筋力の月か選んでください: ')

    if month == '筋肥大の月':
        print('レップ数は8~10回です')
    else:
        print('レップ数は1~5回です')

else:
    print('入力が正しくありません')