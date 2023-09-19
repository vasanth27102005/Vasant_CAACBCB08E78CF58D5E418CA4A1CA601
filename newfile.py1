class Player:
    def __init__(self, n, a):
        self.name = n
        self.age = a

    def show(self):
        print("")
        print("Player name: " + self.name)
        print("Age: " + str(self.age))


class CricketPlayer(Player):
    def __init__(self, n, t, a):
        super().__init__(n, a)
        self.type = t

    def show(self):
        super().show()
        print("Player type: " + self.type)


class FootballPlayer(Player):
    def __init__(self, n, t, a):
        super().__init__(n, a)
        self.type = t

    def show(self):
        super().show()
        print("Player type: " + self.type)


class HockeyPlayer(Player):
    def __init__(self, n, t, a):
        super().__init__(n, a)
        self.type = t

    def show(self):
        super().show()
        print("Player type: " + self.type)


c = CricketPlayer("Virat", "Cricket", 36)
f = FootballPlayer("Ronaldo", "Football", 40)
h = HockeyPlayer("Mandeep", "Hockey", 43)
c.show()
f.show()
h.show()
