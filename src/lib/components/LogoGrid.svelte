<script>
    const logos = [
        { name: 'Salesforce', hasCaseStudy: false },
        { name: 'HubSpot', hasCaseStudy: false },
        { name: 'Stripe', hasCaseStudy: false },
        { name: 'Shopify', hasCaseStudy: false },
        { name: 'Atlassian', hasCaseStudy: false },
        { name: 'Zendesk', hasCaseStudy: false },
        { name: 'Slack', hasCaseStudy: false },
        { name: 'Mailchimp', hasCaseStudy: false },
        { name: 'Airtable', hasCaseStudy: false },
        { name: 'Notion', hasCaseStudy: false }
    ];
</script>

<section class="py-12 bg-white border-b border-gray-200 font-sans">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <p class="text-center text-[10px] uppercase tracking-widest text-gray-500 font-bold mb-8">
            TRUSTED BY FORWARD-THINKING B2B BRANDS
        </p>

        <div class="grid grid-cols-2 md:grid-cols-5 gap-0 border-t border-l border-gray-200">
            {#each logos as logo}
                <div class="flex items-center justify-center p-6 border-r border-b border-gray-200 h-24 relative group">
                    <span class="text-lg md:text-xl font-bold text-gray-300 group-hover:text-gray-600 transition-colors">
                        {logo.name}
                    </span>
                </div>
            {/each}
        </div>
    </div>
</section>
