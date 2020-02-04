# text_filter
文本敏感词过滤（附1w+的中文词敏感词库）

USAGE:

    >>> f = DFAFilter()
    >>> f.add("sexy")
    >>> f.filter("hello sexy baby")
    hello **** baby
