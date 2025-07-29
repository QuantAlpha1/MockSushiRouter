This is a mock or simplified version of a SushiSwap router contract. Here's why it's a "mock sushi":

    Simplified Functionality:

        The getAmountsOut function just returns amountIn * 2 instead of performing real price calculations

        The swap functions (swapExactETHForTokens and swapExactTokensForETH) don't actually perform swaps - they just emit events

    Testing Purpose:

        It includes events like SwapExecuted that would be useful for testing

        It has the basic interface structure of a real DEX router but without the complex logic

    Placeholder Values:

        The contract name is "SushiswapRouter" (note the spelling difference from the real "SushiSwap")

        It accepts the same parameters as a real router but doesn't implement the actual functionality

This would be useful for:

    Testing frontends without real transactions

    Development environments

    Educational purposes

    Mocking in unit tests

The contract is safe (as it doesn't actually handle funds), but obviously shouldn't be used in production as it doesn't perform real swaps or price calculations.
