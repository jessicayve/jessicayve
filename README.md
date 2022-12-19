

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=jessicayve&theme=radical)](https://git.io/streak-stats)


return DefaultTextStyle(
  style: const TextStyle(
    fontSize: 20.0,
  ),
  child: AnimatedTextKit(
    animatedTexts: [
      WavyAnimatedText('Hello World'),
      WavyAnimatedText('Look at the waves'),
    ],
    isRepeatingAnimation: true,
    onTap: () {
      print("Tap Event");
    },
  ),
);
