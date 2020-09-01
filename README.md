USING HILL CLIMBING

    function HILL-CLIMB(problem):

      current = initial state of problem

      repeat:

        neighbor = highest valued neighbor of current

        if neighbor not better than current:

          return current

        current = neighbor


