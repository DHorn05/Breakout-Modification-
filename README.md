# Breakout-Modification-

- Added randomized colored block durability, three yellow bonus blocks per level that spawn extra balls, multiball paddle support, and faster paddle movement to make gameplay more varied and energetic.

- BallManager and the IBallLauncher abstraction, and modified Game1, Ball, Block, BlockManager, Paddle, PaddleController, and ScoreManager so each component handles its own responsibility while Game1 coordinates them.

- Replaced static score, life, and level state with the IScoreManager interface, and added per-ball state and block-contact tracking to support multiball and avoid repeatedly damaging a block during one contact.

- Improved maintainability by separating ball management and component coordination and reducing direct dependencies.
