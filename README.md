# Discord.py-random-choices
This is a code which will help u make a discord bot with random answers, hope it helps

@client.command(aliases = ["8ball", "test"])
async def _8ball(ctx, * , question):
    responses = [
        "Yes of course",
        "No I don't think so buddy",
        "Obsolutely",
        "Get lost",
        "No way, you believe in that",
        "I don't know",
        "Okay, no way that is happening",
        "Good luck with that, cause its not happening",
        "Its not about luck, its about hard work",
        "Blah, Blah, Blah"
    ]
    await ctx.send(f'Question = {question}\nAnswer: {random.choice(responses)}'
