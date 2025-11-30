{
  "meta": {
    "source": "https://thielfellowship.org/",
    "retrieved_at": "2025-11-30",
    "notes": "Структура и компоненты восстановлены по HTML-разметке. Точные значения цветов и деталей CSS не видны из кода, поэтому все hex-значения — предположения и должны быть уточнены инспектором в браузере."
  },
  "foundations": {
    "layout": {
      "page": {
        "max_width_px": 960,
        "padding_x_desktop_px": 24,
        "padding_x_mobile_px": 16,
        "padding_y_section_px": 64,
        "alignment": "centered_column",
        "notes": "Ощущение одно-колоночной страницы с центровкой основных блоков и крупными вертикальными отступами между секциями."
      },
      "grid": {
        "type": "single_column",
        "columns": 1,
        "section_order": [
          "header",
          "hero",
          "what_section",
          "why_section",
          "as_seen_in",
          "footer"
        ],
        "notes": "Секции идут строго вертикальным стеком без сложной сетки."
      }
    },
    "colors": {
      "palette": {
        "background_primary": {
          "role": "Основной фон страницы",
          "value_hex_guess": "#FFFFFF",
          "confidence": 0.95,
          "notes": "Чистый белый фон."
        },
        "text_primary": {
          "role": "Основной текст",
          "value_hex_guess": "#111111",
          "confidence": 0.8,
          "notes": "Почти чёрный текст для высокой контрастности."
        },
        "text_muted": {
          "role": "Вторичный текст, подписи, копирайт",
          "value_hex_guess": "#555555",
          "confidence": 0.6,
          "notes": "Слегка приглушённый серый."
        },
        "border_subtle": {
          "role": "Тонкие разделители/границы (если есть)",
          "value_hex_guess": "#E5E5E5",
          "confidence": 0.4,
          "notes": "Если используются разделители — они выглядят как светло-серые линии."
        },
        "accent_primary": {
          "role": "Ссылки и кнопка Apply Now",
          "value_hex_guess": "#1F4FFF",
          "confidence": 0.4,
          "notes": "Вероятный синий акцент для ссылок/кнопок. Требует проверки по реальному CSS."
        }
      },
      "usage": {
        "links": {
          "default": "accent_primary",
          "hover": "accent_primary (подчёркивание или небольшое изменение яркости)",
          "visited": "accent_primary (без явного изменения цвета)",
          "notes": "Ссылки в навигации и внутри текста визуально должны быть отличимы по цвету и/или подчёркиванию."
        },
        "buttons": {
          "primary": {
            "background": "accent_primary",
            "text": "background_primary",
            "border": "accent_primary"
          },
          "ghost": {
            "background": "transparent",
            "text": "accent_primary",
            "border": "accent_primary"
          },
          "notes": "Главная кнопка Apply Now, вероятно, в заливке. Возможно, в футере/навигации используется вариант без заливки."
        }
      }
    },
    "typography": {
      "font_families": {
        "base": {
          "name_guess": "System UI / Sans-Serif",
          "stack_guess": "-apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif",
          "confidence": 0.6,
          "notes": "По ощущениям — современный системный гротеск без брендового кастомного шрифта."
        }
      },
      "scale": {
        "h1": {
          "role": "Главный хедлайн на hero",
          "font_family": "base",
          "font_size_rem": 2.5,
          "font_weight": 700,
          "line_height": 1.1,
          "letter_spacing_em": 0,
          "case": "sentence",
          "notes": "Текст: “The Thiel Fellowship gives $200,000…” — выделенный крупный заголовок."
        },
        "h2": {
          "role": "Заголовки секций (What, Why, As seen in)",
          "font_family": "base",
          "font_size_rem": 1.5,
          "font_weight": 700,
          "line_height": 1.2,
          "notes": "Секции помечены как `## What`, `## Why`, `## As seen in`."
        },
        "h3": {
          "role": "Подзаголовки/микроразделы (Contact, Navigate)",
          "font_family": "base",
          "font_size_rem": 1.125,
          "font_weight": 700,
          "line_height": 1.3,
          "notes": "Используется для подпунктов в футере (`### Contact`, `### Navigate`)."
        },
        "body": {
          "role": "Основной текст параграфов",
          "font_family": "base",
          "font_size_rem": 1.0,
          "font_weight": 400,
          "line_height": 1.6,
          "notes": "Описание программы, ответы в FAQ, тексты цитат."
        },
        "body_small": {
          "role": "Служебный текст, копирайт",
          "font_family": "base",
          "font_size_rem": 0.875,
          "font_weight": 400,
          "line_height": 1.5,
          "notes": "Копирайт, короткие подписи."
        },
        "numeric_label": {
          "role": "Крупные номера блоков (01, 02, 03)",
          "font_family": "base",
          "font_size_rem": 1.25,
          "font_weight": 600,
          "letter_spacing_em": 0.1,
          "notes": "Номера секций внутри блока “Why”."
        },
        "quote": {
          "role": "Цитаты (Plato, Margaret Mead, Kanye)",
          "font_family": "base",
          "font_size_rem": 1.0,
          "font_style": "italic",
          "notes": "Строки цитат и подпись автора."
        }
      }
    },
    "spacing": {
      "scale_px": {
        "xs": 4,
        "sm": 8,
        "md": 16,
        "lg": 24,
        "xl": 32,
        "2xl": 48,
        "3xl": 64
      },
      "section_spacing": {
        "between_sections_px": 64,
        "between_heading_and_body_px": 16,
        "between_paragraphs_px": 12,
        "between_list_items_px": 8,
        "notes": "Вертикальные отступы ощущаются довольно крупными, текст ‘дышит’."
      }
    },
    "radii": {
      "button_radius_px": 4,
      "input_radius_px": 4,
      "card_radius_px": 0,
      "notes": "Сайт выглядит строго и минималистично; если и есть скругления, они небольшие."
    },
    "shadows": {
      "use_shadows": false,
      "notes": "Визуально сайт опирается на чистую типографику и белое пространство, без тени-карточек."
    },
    "breakpoints": {
      "xs": {
        "label": "mobile",
        "min_width_px": 0
      },
      "sm": {
        "label": "small_tablet",
        "min_width_px": 640
      },
      "md": {
        "label": "tablet",
        "min_width_px": 768
      },
      "lg": {
        "label": "desktop",
        "min_width_px": 1024
      },
      "xl": {
        "label": "wide_desktop",
        "min_width_px": 1280
      },
      "notes": "Типичный набор брейкпоинтов для адаптивной вёрстки; точные значения нужно сверить в devtools."
    }
  },
  "components": {
    "Header": {
      "role": "Верхняя навигация сайта.",
      "structure": {
        "logo": {
          "type": "text_or_logo_mark",
          "text_guess": "Thiel Fellowship (или логотип-щит)",
          "click_behavior": "go_to_home"
        },
        "nav_links": [
          {
            "label": "FAQ",
            "href": "/faq",
            "kind": "link"
          },
          {
            "label": "Apply",
            "href": "/apply",
            "kind": "primary_cta_link"
          }
        ]
      },
      "layout": {
        "orientation": "horizontal",
        "alignment": "space_between",
        "padding_y_px": 16,
        "padding_x_px": 16
      },
      "states": {
        "sticky": false,
        "mobile_menu": "none_or_simple_collapse"
      },
      "notes": "Минимальный хедер без сложных выпадающих меню."
    },
    "Hero": {
      "role": "Первый экран, вводящий в суть программы.",
      "content": {
        "title": "The Thiel Fellowship gives $200,000 to young people who want to build new things instead of sitting in a classroom.",
        "subtitle": "Two years. $200,000. Some ideas can’t wait.",
        "primary_cta": {
          "label": "Apply Now",
          "href": "/apply"
        }
      },
      "layout": {
        "alignment": "center",
        "max_width_px": 720,
        "spacing": {
          "title_to_subtitle_px": 16,
          "subtitle_to_cta_px": 24
        }
      },
      "visual_style": {
        "background": "background_primary",
        "title_typography": "h1",
        "subtitle_typography": "body",
        "cta_variant": "primary"
      }
    },
    "Section_What": {
      "role": "Описание того, что такое Fellowship.",
      "heading": {
        "text": "What",
        "level": "h2"
      },
      "body": {
        "type": "paragraph",
        "text": "Founded by technology entrepreneur and investor Peter Thiel in 2011, the Thiel Fellowship is a two-year program for young people who want to build new things. Thiel Fellows skip or stop out of college to receive a $200,000 grant and support from the Thiel Foundation’s network of founders, investors, and scientists."
      },
      "layout": {
        "alignment": "left_on_desktop_center_on_mobile",
        "max_width_px": 720,
        "spacing_top_px": 64
      }
    },
    "Section_Why": {
      "role": "Блок с тремя причинами / преимуществами.",
      "heading": {
        "text": "Why",
        "level": "h2"
      },
      "items": [
        {
          "number_label": "01",
          "title": "A different path for everyone",
          "quote": {
            "text": "“Knowledge that is acquired under compulsion obtains no hold on the mind.”",
            "author": "Plato"
          },
          "description": "College can be good for learning about what’s been done before, but it can also discourage you from doing something new. Each of our fellows charts a unique course; together they have proven that young people can succeed by thinking for themselves instead of following a traditional track and competing on old career tracks."
        },
        {
          "number_label": "02",
          "title": "Freedom to get stuff done",
          "quote": {
            "text": "“My grandmother wanted me to have an education, so she kept me out of school”",
            "author": "Margaret Mead"
          },
          "description": "Pursue ideas that matter instead of mandatory tests. Take on big risks instead of big debt. How you spend your two years in the Fellowship is up to you — we’re here to help, but we won’t get in the way."
        },
        {
          "number_label": "03",
          "title": "Our network is yours",
          "quote": {
            "text": "“That major that she majored in don't make no money / But she won't drop out, her parents'll look at her funny”",
            "author": "Kanye"
          },
          "description": "The hardest thing about being a young entrepreneur is that you haven’t met everyone you’ll need to know to make your venture succeed. We can help connect you — to investors, partners, prospective customers — in Silicon Valley and beyond."
        }
      ],
      "layout": {
        "items_orientation": "vertical_stack_on_mobile",
        "items_maybe_two_column_on_desktop": false,
        "spacing_between_items_px": 32,
        "alignment": "left_or_center",
        "max_width_px": 720
      },
      "visual_style": {
        "number_typography": "numeric_label",
        "title_typography": "h3_or_body_bold",
        "quote_typography": "quote",
        "description_typography": "body"
      }
    },
    "Section_AsSeenIn": {
      "role": "Соцдоказательства через медиа-цитаты.",
      "heading": {
        "text": "As seen in",
        "level": "h2"
      },
      "items": [
        {
          "source": "The New York Times",
          "quote": "“Thanks to the Thiel Fellowship, access to some of the nation’s most successful businesspeople is quick and easy.”"
        },
        {
          "source": "TechCrunch",
          "quote": "“Thiel’s fellowship pays kids a stipend that liberates them to work on ways to improve the world, rather than saddling them with debt. They get mentorship, workshops, connections to resources, and an alumni network without a formal alma mater.”"
        },
        {
          "source": "Wall Street Journal",
          "quote": "“Not long ago, dropping out of school to start a company was considered risky. For this generation, it is a badge of honor, evidence of ambition and focus.”"
        }
      ],
      "layout": {
        "items_orientation": "vertical_list",
        "max_width_px": 720,
        "spacing_between_items_px": 24
      },
      "visual_style": {
        "source_typography": "body_small_bold_or_caps",
        "quote_typography": "body_italic_or_regular"
      }
    },
    "FAQ_Page": {
      "path": "/faq",
      "role": "Список часто задаваемых вопросов.",
      "structure": {
        "intro_banner": {
          "title": "FAQ",
          "subtitle": "The Thiel Fellowship gives $200,000 to young people who want to build new things instead of sitting in a classroom.",
          "heading_level": "h1_or_h2"
        },
        "qa_list": {
          "type": "stacked_questions",
          "question_typography": "h3_or_body_bold",
          "answer_typography": "body"
        }
      },
      "layout": {
        "max_width_px": 720,
        "spacing_between_questions_px": 24
      },
      "notes": "Каждый вопрос — заголовок + один абзац ответа; без аккордеонов по данным HTML."
    },
    "JobBoard_Page": {
      "path": "/jobs",
      "role": "Список компаний Thiel Fellows, которые нанимают.",
      "heading": {
        "title": "Job Board",
        "subtitle": "The Thiel Fellowship job board.",
        "heading_level": "h1"
      },
      "structure": {
        "intro_text": "Below are Thiel Fellowship companies who are hiring now.",
        "company_list": {
          "type": "unstyled_text_list",
          "items": "plain company names as links or text",
          "example_items": [
            "Adept",
            "AirGarage",
            "Alloy",
            "Altro",
            "Amber Agriculture",
            "Aunt Flow",
            "Beek",
            "Betr",
            "Biofire",
            "Blur",
            "Branch",
            "BRINC",
            "Clay",
            "CodeGem",
            "CoMind",
            "Community Phone",
            "CropSafe",
            "Cryopets",
            "Curative",
            "Curious Addys",
            "Dandy",
            "Depict",
            "Dreambound",
            "Eden",
            "Etched",
            "Evervault",
            "ExpressionMed",
            "Figma",
            "Firm",
            "Flex",
            "Freenome",
            "Freshline",
            "Genetesis",
            "Glorify",
            "Hack Club",
            "HelpWear",
            "Hightouch",
            "Immutable",
            "Indent",
            "Italic",
            "Kafene",
            "Keep",
            "Knot",
            "Legalist",
            "Lendtable",
            "Locke Bio",
            "LogRocket"
          ]
        }
      },
      "layout": {
        "max_width_px": 720,
        "spacing_between_companies_px": 8
      }
    },
    "Footer": {
      "role": "Служебная информация, контакт и навигация.",
      "sections": {
        "contact": {
          "heading": "Contact",
          "items": [
            {
              "type": "email",
              "label": "team@thielfellowship.org",
              "href": "mailto:team@thielfellowship.org"
            }
          ]
        },
        "copyright": {
          "text_lines": [
            "© 2025 The Thiel Foundation.",
            "All rights reserved."
          ]
        },
        "navigate": {
          "heading": "Navigate",
          "links": [
            {
              "label": "Apply Now",
              "href": "/apply"
            },
            {
              "label": "Thiel Fellow Job Board",
              "href": "/jobs"
            }
          ]
        }
      },
      "layout": {
        "orientation_desktop": "three_columns (Contact / Copyright / Navigate) or vertical_stack",
        "orientation_mobile": "vertical_stack",
        "padding_y_px": 32,
        "padding_x_px": 16
      },
      "visual_style": {
        "background": "background_primary",
        "text_typography": "body_small",
        "heading_typography": "h3"
      }
    },
    "Button": {
      "variants": {
        "primary": {
          "background_color": "accent_primary",
          "text_color": "background_primary",
          "border_color": "accent_primary",
          "padding_y_px": 10,
          "padding_x_px": 20,
          "radius_px": 4,
          "font_weight": 600,
          "interaction": {
            "hover": "background slightly darker, maybe #173BCC",
            "focus": "visible_outline_or_shadow",
            "active": "small darkening"
          }
        },
        "link_like": {
          "background_color": "transparent",
          "text_color": "accent_primary",
          "border_color": "transparent",
          "notes": "Используется для ссылок Apply/FAQ в хедере."
        }
      }
    },
    "Link": {
      "text_decoration": {
        "default": "none_or_subtle",
        "hover": "underline",
        "focus": "outline_or_underline"
      },
      "color": "accent_primary"
    }
  },
  "content_style": {
    "voice": {
      "tone": [
        "прямой",
        "контрастирующий с традиционным образованием",
        "немного провокационный"
      ],
      "keywords": [
        "$200,000",
        "two-year program",
        "build new things",
        "instead of sitting in a classroom",
        "skip or stop out of college",
        "network of founders, investors, and scientists"
      ],
      "notes": "Копирайт строится вокруг противопоставления университету и акцента на действии/созидании."
    },
    "structure_patterns": {
      "hero_pattern": "Большое обещание в одном предложении + короткий слоган + CTA.",
      "why_pattern": "Нумерованный блок (01/02/03) → заголовок → цитата → объяснение.",
      "social_proof_pattern": "Источник в эм-дэше + короткая цитата из медиа.",
      "faq_pattern": "Классический Q&A c прямыми ответами без маркетинговой воды."
    }
  }
}